# Test Plan – Job Card CRUD Application ServeCraft

## 1. Project Overview
This Test Plan defines the testing activities, scope, schedule, and responsibilities for validating the Job Card CRUD Application fro ServeCraft

## 2. Objectives
- Validate all CRUD functionality  
- Ensure API reliability and correctness  
- Confirm UI behavior and user flows  
- Validate form and field-level rules  
- Ensure integration between UI and backend  
- Provide automation coverage for key API flows  

## 3. Scope

### In Scope
- API testing (manual) + Automation testing 
- Front-end functional testing  
- Integration testing  
- Exploratory testing  

### Out of Scope
- Performance testing  
- Security penetration testing  
- Cross-browser compatibility matrix  
- Mobile testing  
- UI automation 

## 4. Test Items
- Job Card Listing  
- Search & Filter  
- Pagination  
- Create Job Card  
- Edit Job Card  
- Delete Job Card  
- API endpoints supporting all CRUD operations  

## 5. Test Approach

### 5.1 API Testing ()
API testing was a core component of this project.  
We validated:
- CRUD endpoints  
- Pagination  
- Filtering  
- Error responses  
- Data integrity  
- Negative scenarios  

### 5.2 Front-End Testing
UI testing focused on:
- Navigation  
- Form validation  
- Error messages  
- Search and filter behavior  
- Pagination  
- User experience consistency  

### 5.3 Automation (Karate)
Karate was used to automate:
- Core API flows  

This ensures repeatability and reduces manual effort.

## 6. Test Deliverables
- Test Strategy  
- Test Plan  
- Test Cases (Excel)  
- Test Execution Report  
- Automation Scripts (Karate)  
- QA Sign-off  

## 7. Roles & Responsibilities
| Role | Responsibility |
|------|----------------|
| QA Engineer | Mulamuleli  |
| Developer | Ntokozo |
| Product Owner | Dovi |
| QA Lead | Mulamuleli |

## 8. Schedule
- Test planning  
- Test case design  
- API testing  
- UI testing  
- Automation execution  
- Regression cycle  || Not yet started
- Final sign-off 

## 9. Exit Criteria
- All test cases executed  
- All passed 100% pass rate achieved)  
- No defects found  
- Automation suite executed successfully  
- Application stable and ready for release  

## 10. Summary
Testing was completed successfully across API and UI 
API testing went exceptionally well, with all endpoints behaving as expected.  
Front-end testing confirmed stable user flows and correct validation.  
Karate automation has been initiated and will be made available will be executed in UAT
