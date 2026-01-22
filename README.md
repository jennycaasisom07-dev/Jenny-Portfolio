# Business Analyst Portfolio

This repository demonstrates my work as a Business Analyst, focusing on:
- Translating business needs into clear, structured requirements
- Writing user stories and testable acceptance criteria
- Managing change requests using As-Is / To-Be analysis
- Supporting product delivery with Dev, QA, and Design teams

## Sample Domains
- Content Management Systems
- Role-based access control
- Platform performance & scalability

## What This Repository Shows
- Well-structured requirement documentation
- Clear and testable acceptance criteria
- Practical change management approach
- Collaboration-ready artifacts for cross-functional teams

## Repository Structure
- **01-prd**: Product Requirement Documents
- **02-user-stories**: User stories and acceptance criteria
- **03-change-requests**: Change request examples
- **04-templates**: Reusable BA templates
- **05-release-notes**: Sample release documentation

> Note: All examples are anonymized and created for demonstration purposes only.


# PRD: Content Library Folder Limit

## Problem Statement
Unlimited folder creation leads to usability challenges and system performance degradation.

## Objective
Introduce controlled folder creation limits while maintaining flexibility for users.

## Scope
### In Scope
- Folder creation limits per level
- UI validation and helper messages

### Out of Scope
- File upload limits
- Auto-generated folders

## Stakeholders
- Product Owner
- Engineering
- QA
- Design


## User Story
As an Authorized User  
I want to create folders within a defined limit  
So that the system remains usable and performant.

## Acceptance Criteria
- Maximum 30 folders allowed at the root level
- Create Folder button is disabled when the limit is reached
- A helper message explains the folder limit
- Existing folders remain accessible and usable



## Change Request: Folder Limit Update

### As-Is
There is no restriction on the number of folders that can be created per level.

### To-Be
Introduce a maximum folder limit per level with both UI and API validation.

### Impact Analysis
- UI changes required to disable folder creation
- Additional validation logic on the backend
- QA regression testing for folder-related actions

### Decision
Approved for Release 6.0



###Template

## User Story
As a [role],  
I want [feature],  
So that [business value].

## Acceptance Criteria
- Given …
- When …
- Then …

## Notes
- Dependencies
- Assumptions



## Change Request Title

### As-Is
Describe the current behavior or process.

### To-Be
Describe the proposed change.

### Impact
- Scope
- Timeline
- Risk

### Approval
- Product:
- Technical:



# Sample Project: Content Library Folder Limit

## Business Problem
Unlimited folder creation impacts system performance and user experience.

## Requirement
Enforce folder creation limits per level.

## User Story
As an Authorized User,  
I want to create folders within a defined limit,  
So that system performance remains stable.

## Acceptance Criteria
- Maximum 30 folders at root level
- Folder creation disabled when limit is reached
- Clear validation message displayed

## Change Request
- As-Is: No folder limit enforced
- To-Be: Folder limits enforced per level
