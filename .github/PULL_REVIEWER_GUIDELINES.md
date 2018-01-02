# Peer Reviewer Guidelines
As a reviewer, your review is guided by two overarching questions: 
> Question 1: Does this accomplish the intent of the ticket? 

> Question 2: Is this code able to be understood through code structure or documentation? 


### Suggesting Fixes: 
Reviewers are encouraged to offer feedback and suggestions for improvement. Below is a brief summary of the levels of feedback that may be given. 

Major - This presents a structural issue that if not fixed, WILL/COULD lead to issues. The reviewer MUST “request changes” along with providing a justification. 

Minor - This change is optional, having no significant impact. The reviewer MAY NOT “request changes”. 

Investigate - This change may introduce breaking functionality, reviewer is granted discretion using “request changes” if it is unclear if the change will break existing functionality. Justification must be included. 

### Fix Comment template: 
```
[Major, Minor, Investigate] - Concise problem statement. 

Reason: Why is this change justified?  

Snippet: If “request changes” has been selected, and a code refactor is required, a code block detailing the changes must be included. 
```

### Handling Escalations
- Should differences in a pull request require escalation, an additional senior engineer may be requested to review. 
- No more than two Senior Engineers may be pulled for escalation resolution before requiring escalation to Director level management. 
