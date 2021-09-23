# ConsenSys Blockchain Developer Bootcamp Final Project
ConsenSys Blockchain Developer Bootcamp Final Project

## Problem 
- People like remote work 
- Full time employees are seeking freelancers jobs to increate their income / does things of their interests 
- Companies looking for entry to holding crytocurrencies as comapny capital  

## Solution 
- Private Blockchain for Employee Bounties Program 
- [Solution Deck](https://pasteapp.com/p/QpLUGqJKG6D?view=1u5TDFy310K) - developing 

## Scope of MVP

### Components Overview

- Accounts management
- **Tasks management**
- Web-based editors (use blockchain technology to measure time spent and actual activities)
- **Rating system**
- **Rewards distribution**
- Fund management

### MVP Roles 
- Task creator
- Contributors
- Reviewer

### MVP User Stories 
- User can create task and define its requirement/ expectation and expected deadline, limit of contributors
- User can choose to contribute to tasks
- User can earn rewards by contributing to projects and reviewing others' work

### Tasks management (MVP version)
1. Anyone in the same organisation can create task 
2. A task must have requirement/ expectation, expected deadline, limits of contributors, estimated bounties amount  
3. Link to submit work anonymously (out of blockchain) 

### Rating System (MVP version)
1. The system will release work ready for review to users automatically based on
    1. their availability 
    2. their credibility score
    3. their area of interests / expertise (?)
2. All works are anonymous, all reviews & comments will be anonymous
3. The system will evaluate reviews by each reviewers' weighting and try to locate irregular reviewers (untruthful review may be indicated by regular outlier rating), which will affects their credibility score, which in turns affects the likelihood of receiving review works. 

### Rewards Distribution (MVP version)
1. Via wallet accounts 
2. Bounties distribution ratio 
    1. ~60% contributors 
    2. ~40% reviewers 
3. Suggested contributors to reviewers ratio 1 Contributor to 7 Reviewers
4. Example
    1. Reward $300, 3 Contributors, ~ 21 Reviewers 
        1. Each Contributor gets $30 - $90 depending on the ratings  
        2. Each Reviewers gets $5.7