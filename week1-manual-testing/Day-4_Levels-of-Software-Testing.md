Levels Of Sofware Testing
-------------------------

SDLC Phases

Requirement Analysis & Gathering phase
Design
Coding
Testing
Deployment
Maintenance

There are mainly 4 levels of software testing

Unit Testing: checks if sofware component are fulfilling functionalities or not. It is done by developers in development environment.

Integration Testing: checks the data flow from one modeule to another module. Integration means combining. For example , In this testing phase difference modues are combined and tested as a group to make sure that integrated system is ready for system testing.

Approaches of Integration Testing
---------------------------------
1) Top down integration - In Top-Down Integration Testing, the high-level modules are integrated and tested first. i.e Testing from the main module to the submodule. In this approach stubs are used as a dummy module for the missing module if submodule is under development or not available. Stubs are called by the module under test

2) Bottom up integration : In Bottom Up Integration Testing, the low-level modules are integrated and tested first i.e Testing from sub-module to the main module. In this approach drivers are used as a temporary module for mission module if module is under development or not available. Drivers , it calls the module to be tested.

Different Modules	Module functionality
---------------		----------------------
Module-1		Login page of the web application
Module-2		Home-page of the web application
Module-3		Print Setup
Module-4		Log out page


System Testing: System testing is performed on integrated system. It involved load , performace testing, reliability and security testing.  It allows checking system's compliance as per the requirement.  It focus on 

Functional testing
non functional testing
UserInterface testing
Usability testing

It is end-to-end testing where the testing environment is parallel to the production environment. In the third level of software testing, we will test the application as a whole system. 

User Acceptance Testing (UAT): Acceptance testing is conducted by the customer/stakeholder/users/domain expert for their satisfaction before accepting the final product. This is fourth level of testing.
