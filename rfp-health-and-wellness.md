# RFP - Hunt Game

## Statement of Purpose

We wish to use the popularity of mobile technology to increase student awareness and interest in health and wellness. We are looking for an application that uses mobile devices to encourage users to provide health-related data through fun group challenges and sharing of results. 

## Vision

We would like to create an app that can be accessed on different mobile devices, as well as web browsers. The typical users would use their mobile devices to participate in wellness challenges and enter the relevant daily data. Initial data categories include:
 - Step count
 - Hydration level
 - Amount of sleep
 - Servings of fruit consumed
 - Servings of vegetables consumed
 - Number of calories consumed

Participating users would be assigned to group challenges by an administrator, which would include daily wellness targets. An administrator would also be able to access and monitor the data of all participants, create and modify groups and challenges, and share certain challenge results among group members.

In addition, all users would have the ability to view data from previous challenges in which they have participated.

## Functional Requirements

Create a progressive web app (or native application) with authentication and 
authorization. The following roles are suggested:

1. Administrator (access to all information including app settings)
1. User (access to their content)

Administrators can:

1. View and download all data entered by users
1. Create and manage user groups
1. Create and manage group challenges
1. Download all group and challenge data
1. Share challenge results with group members

Anu user can:

1. Create and edit a user profile
1. Accept or reject a group assignment
1. Enter, view, and modify personal data as needed
1. View challenge data for the rest of their group
1. View data from past challenges

Security must be addressed throughout the app.

The app should provide convenient and clear controls
for administrator functions.

The app should allow users to enter, view, and modify data
quickly and easily, using modern UI elements.

The app should provide clear confirmation when an operation
is completed.

The app should follow professional and friendly design and 
user experience principles.

The app should be responsive, able to work well on various mobile devices 
from phones to laptops and tablets in various orientations. 

The app should provide a customizable theme using NW Bearcat colors. 
This theme should be able to be swapped if the app is used at other schools. 

The app must work on:

- an iPhone SE
- an Android device
- a laptop computer
- an iPad

Expected (suggested) entites may include:

User (includes admins) 

  - email
  - password
  - username
  - date created
  - date last accessed

DailyLevel (one measurement per category per user per day)

  - date of measurement
  - step count
  - hydration (amount of water consumed)
  - hours of sleep
  - servings of fruit
  - servings of vegetables
  - total calories

Group (a group has 0 or more members)

  - group name
  - creator (administrator)
  - date created
  - date last edited

GroupMember mapping

  - DateInvited
  - DateAcceptedInvite
  - DateRejectedInvite
  - DateLeftGroup

Challenge (a challenge has 0 or more targets)

   - challenge name
   - designer (administrator)
   - date created
   - date last accessed

Target (a target belongs to 0 or more challenges)

   - target name
   - target description
   - target numerical goal

ChallengeTarget mapping

Optional: Competition (groups compete around a challenge)

## Bidder Qualifications

Teams that bid on the RFP must be able to:

1. Specify the project.
1. Discuss and clarify details with our acting client before beginning.
1. Implement functionality within times agreed to in the contract.
1. Use professional tools for collaboration.
1. Use professional tools for project management and tracking. 
1. Communicate professionally in person (as the environment allows).
1. Communicate professionally remotely (as the situation requires).

## Performance Metrics

Teams will be judged on their performance to meet the proposed contract deliverables.


## Schedule (Duration in Weeks)

* Module 1: Rapid architecture/data/UI design & proposal competition (~2)
* Module 2: Synthesis of design and initial planning (~2)
* Module 3-6: Implementation iterations
* Module 7: Early release and contract finalization (~1)

## Project Conception and Initialization

Module 1 will include the rapid development of a proposal 
to be presented in Markdown or HTML with in-line images and tables (not Word).

This is quick - occuring at the very beginning of the semester.

This forces hard decisions about entities, screens, and functionality. 
Good effort this this phase will 
make the rest of the project much more effective. 

The proposal should include the following sections.

* Statement of Purpose
* Overview
* Benefits
* Epics / User Stories / Tasks
* Acceptance criteria checklist
* Contract scope / budget / schedule (2 semesters)
* User interface sketches (e.g. Figma or paper)
* Technology stack descriptions
* E-R diagram displayed and described
* Consistent set of sample data in Excel, use one sheet for each entity
* Risks and assumptions

Module 1 teams will be assigned at random for this initial design competiion. 

These teams will be disbanded at the end of Module 1. 

Module 1 is a friendly competition. The teams and client will 
work together to choose the best parts of each proposal and use this to direct the 
remaining effort. 

## Project Definition and Planning

Based on the information learned from all teams rapid response in Module 1, 
we will reorganize and begin a clear, consolidated design vision in Module 2. 

Module 2 will include the development of a detailed contract 
for this semester's remaining work.  Here is where we decide exactly what 
products will be created and what platforms or technology stacks will be used 
for each instance. 

Designs and plans will be presented in Markdown or HTML 
with in-line images and tables (not Word).

We recommend different teams try different data stores, 
architecture approaches (e.g.microservices), and frameworks (e.g. Vue or 
Vanilla JavaScript custom components).

Getting data and user interface correct FIRST are critical. 

NO WORK MAY begin on any UI until the client and mentor have signed a sketch. 

The contract will specify:

* Purpose
* Overview
* Benefits
* Epics / User Stories / Tasks
* Acceptance criteria checklist
* Functional requirements
* Performance requirements (within range of values)
* Other requirements
* User interface sketches (e.g. Figma or paper)
* E-R diagram
* Sample data
* Stack description (including expected tools, technologies, libraries, more)
* Risks and assumptions
* Deliverable artifacts
* Scope
* Milestones
* Schedule and Iteration Plan
* Budget
* Test plan with requirements
* Bid amount

## Payment, Incentives, and Containment

If contract requirements are met 1 7-day week ahead of schedule 
to the satisfaction of the client, 
students are eligible for a 2.5% bonus (based on the total points possible) 
for the associated deliverable.

## Terms and Conditions

Code and applications should be open-source and 
licensed under the Apache 2.0 license. 

## Evaluation Criteria

The client will provide feedback throughout the development process. 

While the client may ask for a requirement change, 
if granted it would require a modification of the contract 
with commensurate elimination of other requirements. 

This would only be applied it there was a critical change in core functionality.  

Typically, requirements changes will be documented 
and would serve as the basis of a change contract.

1. The user interface will be evaluated on aesthetics 
as well as ability to perform a task.  
1. There will be a single major review of every new interface screen.  
1. Good choices will be made for images/color/sound. 
1. Screen space will be used well.  
1. Controls will have signifiers indicating where and how 
operations/input can occur. 
1. Input will be validated. 
1. Appropriate feedback will be employed.  
1. The interface will avoid requiring multiple clicks for common operations.  
1. Confirmation is not required if an operation is easy to undo.  
1. Confirmation is required for operations that cannot be undone.  
1. Default values will be provided for fields.  
1. Do not loose what has been typed if there are errors.  
1. The app will be ADA compliant. 
1. If specified in the contract, support for internationalization may be required.

Note: Correct functionality is not a requirement change.  

## Source

<https://github.com>
