

# Project Happiness Index
    PHI: Project Happiness Index
    
PHI is a fun survey app for employees to indicate their most important values and attributes when working on a new project and working on their current projects.
This app is a web app where the focus is on mobile devices. **Fun** and **mobile** are the key words here. 

[[toc]]

+++
   As a user, I want to filter data from contracts by client manager so that I can see all the contracts per customer from each client manager
- safds 
- -sfsdf
- 
> As a user, I want to filter data from contracts by client manager so that I can see all the contracts per customer from each client manager
#  App
## 1. Welcome Page
### Description 
![Welcome Page Mobile](https://github.com/rubenclaes/happiness_survey/blob/master/Doc/images/0-Welcome-0-mobile-79214381-1515750330.png)
    
 
### User Stories


|#1| _As a user, I want to select multiple attributes, so that I can indicate my most important items when working on new projects_
|-----|----|
|**Acceptance Criteria**|  By default, there is a client manager filter for each client manager in the dropdown list. These are predefined. In the mock-up, we defined only one for Wim. 
|     |After selecting the filter in the dropdown, the dropdown list closes again and the data changes immediately according to the filter.    
|     | Predefined segment filters cannot be removed or changed by the user. So, this means that the edit and delete icons will not be displayed. 

## 2. Attributes New Project
### Description 
![New Project Attributes Page](https://github.com/rubenclaes/happiness_survey/blob/master/Doc/images/1-Nieuw-Project-0-mobile-79215344-1515750567.png)![Behaviour](https://github.com/rubenclaes/happiness_survey/blob/master/Doc/gifs/new_project.gif)
### User Stories
|#1|_As a user, I want to select multiple attributes, so that I can indicate my most important items when working on new projects_
|-----|----|
|**_Acceptance Criteria_**|  By default, no items are selected, and the button at the button is disabled.
|     | After selecting an item in the list of attributes, the background color of this particular item needs to be changed with a different. This makes it clear for the user that the item is "selected"    
|     | The user needs to select at least 10 items (this is defined in the settings part of the app). When he did not choose 10 items a dialog will pop up and he cannot proceed to the next step.
|     | The list of attributes needs to be "scrollable". This way the user has the possibility to select different items that cannot be displayed on the screen initial.
|     | The user cannot proceed to the next page/step of the app when he didn't select the minimal items. Therefore the button at the bottom will be disabled.    |

|#2|_As a user, I want to see how many attributes I selected, so that I have a clear overview of how many items I still can select_ 
|-----|----|
|Acceptance Criteria|  By default, the counter is displayed and has the value "0" 
|     |After selecting an item in the list of attributes, the counter value will change. It will add up in value by "1".
|     | The counter needs to be "sticky" positioned. This means that the counter will be visible at all time, also when the users scrolls down or up.

|#3|_As a user, I want to see my progress of completing the survey, so that I can see quickly how many steps I need to take to finish the survey_ 
|-----|----|
|Acceptance Criteria|  By default, the "stepper" is displayed at the top of the app and is "sticky" positioned.  
|     | When the user proceeds to the next step of the app, the sticky progress bar (or stepper) will visualize the step he is in. 


## 3. Attributes Current Project
### Description 
### User Stories
|#1|As a user, I want to select multiple attributes, so that I can indicate my most important items when working on new projects 
|-----|----|
|Acceptance Criteria|  By default, there is a client manager filter for each client manager in the dropdown list. These are predefined. In the mock-up, we defined only one for Wim. 
|     |After selecting the filter in the dropdown, the dropdown list closes again and the data changes immediately according to the filter.    
|     | Predefined segment filters cannot be removed or changed by the user. So, this means that the edit and delete icons will not be displayed. 
## 3. Finish
### Description 
### User Stories

+++

## Admin
### Description 
### User Stories
## 1. Login
### Description 
### User Stories
## 2. Dashboard
### Description 
### User Stories
## 3. Attributes
### Description 
### User Stories
## 4. Settings
### Description 
### User Stories
## 5. Popular Report
### Description 
### User Stories
## 6. Users Report
### Description 
### User Stories
## 7. User Detail
### Description 
### User Stories