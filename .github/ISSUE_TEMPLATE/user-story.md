---
name: User story
about: Access request for Active Directory
title: ''
labels: ''
assignees: ''

---

**As a** system administrator
**I need** access to active directory
**So that** I can process onboarding/offboarding of users

### Details and Assumptions
* new users have to be onboarded
*old users have to be offboarded
*password update requests must be received

```gherkin
Given access is provided
When user requires onboarding/offboarding
Then enable process to update user id in system
