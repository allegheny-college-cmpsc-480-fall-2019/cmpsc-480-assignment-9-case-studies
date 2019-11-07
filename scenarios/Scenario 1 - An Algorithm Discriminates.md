# An Algorithm Discriminates

## Summary

A software developer designs a software that screens the résumés of candidates
applying for a job at her company. She later discovers that the software may be having a
disparate impact on minority communities. She brings the issue up with her boss, who is
reluctant to change the software.

## Scenario

Sandra is a software developer for Emporia, a large retailer that has recently experienced
high attrition rates in their sales department. Her boss tasks her with designing software that the
company can use to screen the résumés of candidates applying for sales positions. Sandra is
supposed to ensure that the software awards a higher recommendation score to applicants who
are more likely to stay on the job longer.

Sandra begins by applying a Principal Component Analysis (PCA) to data from the
résumés of current and past employees to identify the minimal set of features that best correlate
with length of tenure. Based on this data, Sandra designs her software so that it classifies
résumés possessing a high number of these features as “recommended candidates,” and those
lacking them as “non-recommended candidates.”

One year after implementing Sandra’s software, the company’s salesperson attrition rate
falls by nearly 15%. While analyzing the results, however, Sandra notices that 92% of the new
sales employees hired have been white. Concerned that the company may be violating the legal
standards for fair access to employment, she tries to figure out why her software is not
recommending more applicants from minority groups. After some research, Sandra thinks she
has found the underlying cause. The software is only recommending applicants who live in zip
codes less than one mile away from Emporia stores. This is because the PCA she applied to
employee data identified employee zip codes as the metric best correlated to length of tenure.
She infers that this is because employees living in neighborhoods closest to Emporia stores have
much shorter commute times, and thus tend to stay on the job longer. These neighborhoods,
however, have mostly white, middle-class residents. Black and Latino applicants, who make up
about 80% of the candidates applying for sales jobs, tend to live in areas that are further away
from Emporia stores. Because their zip codes are located over a mile away from Emporia stores,
the software is classifying many of these candidates as “non-recommended candidates.”

As a member of the Association for Information Science and Technology (ASIS&T),
Sandra feels as though it is her ethical and professional responsibility to make sure that the
software she has programmed does not have a disparate impact on minority groups. She presents
her findings to Timothy, the head of human resources. She explains that she thinks the company
may inadvertently be violating the disparate impact principle of the Civil Rights Act of 1964.
This principle prohibits employers from using any employment practices that have unjustified
adverse impacts on members of a protected class, such as lower-income persons, minority
groups, or women.

“I’m not only worried that the software is excluding well-qualified applicants,” says
Sandra. “If Emporia continues to use it to screen résumés, I think that the company will risk
facing employment discrimination litigation.”

Timothy is skeptical about Sandra’s claims. “I think it would be a bad idea to change the
software in any way,” he says. “It has done everything we wanted it to,” he continues. “Not only
is our retention rate at the lowest it has been in years, but our sales are up as well. Plus, is it even
possible for a computer program to discriminate?”

Timothy thinks that the application test is only using objective criteria to identify bestqualified
candidates. Sandra tells him that she thinks that there are more appropriate metrics that
the software can use to recommend applicants, but Timothy remains unwilling to modify it in
any way that might undo its recent success.

## Questions

### What are the basic ethical issues this scenario raises?

### As the software developer, what are Sandra’s ethical responsibilities to those who are applying to the job?

### What are her professional and legal responsibilities as an employee of Emporia?

### What would be a more appropriate metric to use in the software to recommend candidates?

## Authors

Jason Ludwig, Kendall Darfler
