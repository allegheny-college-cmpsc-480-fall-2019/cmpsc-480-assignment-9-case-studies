# Choosing Between Speed and Accuracy

## Summary

A software engineer builds a clinical decision support algorithm for a health-related
research study and realizes, upon implementation, that her design is missing critical input.

## Scenario

Andrea recently graduated from college and started her first position as a software engineer at a
large hospital. She has been asked to design a clinical decision support algorithm for a research
grant that the hospital’s Chief of Hematology, Dr. Williams, has received. The algorithm will help
physicians consistently reduce patients’ risk of blood clots with an innovative model that uses realtime
data on leg movement frequency. Leg lifts and ankle movements are known to be helpful for
increasing blood flow during extended periods of sitting. Dr. Williams’ study aims to help at-risk
patients increase the frequency of their habitual leg movements, by alerting them to low movement
during their clinic visits. Physicians will monitor the frequency at which patients habitually move their
legs over the course of a 20-minute visit, and will enter this data into the electronic health record
(EHR). During the visit, if a patient has low habitual leg movement, a real-time alert will appear in
the EHR instructing the physician to talk to the patient about increasing movement frequency.
Andrea is excited to accept the project. She begins designing the algorithm that will detect patient
leg movements, but soon comes across an important question. How often should physicians enter
leg movement data into a patient’s EHR? Every 2 minutes? Every 3 minutes? Or should there be
larger intervals? Although she is unsure, Andrea thinks that with data entry at every 2 minutes, the
algorithm should detect data points as quickly as possible. This should allow for early risk detection,
and will offer quick alerts to physicians. She decides to run her idea by Dr. Williams, who has more
experience with these kinds of issues.

Andrea visits Dr. Williams’ office to get her approval. When Andrea arrives, Dr. Williams is looking
over some papers. Andrea knocks on the door and says, “Hi Dr. Williams, I had a few questions
about the algorithm you wanted me to design.”

Without looking up from her papers, Dr. Williams replies, “Sure, how can I help you?”
“Well, I was unsure how frequently physicians should enter data points into a patient’s EHR. I think
that it would be best if they did it frequently so that the algorithm can detect at-risk patients as
quickly as possible. I don’t think that busy physicians or sick patients should be left waiting for their
health results,” says Andrea.

“Andrea, I trust that you’ll make the right decision. Just get the algorithm done as soon as possible,”
says Dr. Williams, who seems impatient to get back to her own work. Andrea leaves the office and
moves ahead in coding the algorithm. She then runs the algorithm on several test cases and, after
a few revisions, finds that it works as expected. Dr. Williams decides to implement it in the real
clinical setting.

Several weeks after implementing the clinical decision support algorithm within the hospital’s EHR
system, the IT department begins receiving complaints from physicians. Physicians have had a
hard time keeping up with the 2-minute data entry points during their already crammed
appointments. As a result, the system has been alerting them to low movement right away, in
almost all of their patients. Andrea’s design toward high detection speed has led to false positives.
The EHR alert has proven to be an annoyance to physicians, and many have begun to ignore it.
Dr. Williams meets with Andrea and tells her that this has created a major setback in her study.
“Correcting the mistakes of the algorithm has cost physicians valuable time, and now we are
probably missing patients who could actually benefit from the alert,” she says.
Andrea is embarrassed and apologizes. “Is there another way to design the algorithm that might
work better for physicians?” she asks.

Dr. Williams responds, “Well, other physicians would prefer less frequent data entry points. Also,
you should know that low habitual leg movement is defined by no movement over the course of five
minutes, not two.” She explains that using 5-minute increments would improve the algorithm’s
detection accuracy, and would lessen the data-entry burden on physicians.
“I wish I had known this earlier,” Andrea replies.

## Questions

### What are the basic ethical issues this scenario raises?

### How did Andrea’s product affect the workloads of her colleagues in the hospital? Should computer scientists or software engineers be concerned about the effects their products have on their clients?

### How could Andrea have worked differently with Dr. Williams and the hospital’s other physicians in designing the clinical decision support algorithm? What steps could she have taken earlier in her design process?

### Is it a higher priority to a computer scientist or a software engineer to increase detection speed or detection accuracy? Should this even be a choice?

## Authors

Kendall Darfler, Jason Ludwig