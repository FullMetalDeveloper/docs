# Peer Reviewer Guidelines
> Question 1: Does this accomplish the intent of the ticket? 

As Engineers our task is to solve problems. 

> Question 2: Is this code able to be understood through code structure or documentation? 
- As Engineers, we create solutions that are able to be understood by our peers, both technical and non-technical. 

### Suggesting Fixes: 

Major - This presents a structural issue that if not fixed, WILL/COULD lead to issues. The reviewer MUST “request changes” along with justification. 

Minor - This change is optional, having no significant impact. The reviewer MAY NOT “request changes”

Investigate - This change may introduce breaking functionality, reviewer is granted discretion using “request changes” if it is unclear if the change will break existing functionality. Justification must be included. 

Fix template: 
```
[Major, Minor, Investigate] - Concise problem statement. 

Reason: Why is this change justified?  

Snippet: If “request changes” has been selected, and a code refactor is required, a code block detailing the changes must be included. 
```

### Handling Escalations
- Should differences in a pull request require escalation, an additional senior engineer may be requested to review. 
- No more than two Senior Engineers may be pulled for escalation resolution before requiring escalation to Director level management. 
