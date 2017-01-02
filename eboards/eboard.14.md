CSC322.01 2016F, Class 14: Iteration 1: Day 3
=============================================

_Overview_

* Preliminaries.
    * Admin.
    * Upcoming Work.
    * Questions.
* Reminder: Written reports.
* Reminder: Presentations format.
* Prep Time.
* Presentations.
* Time to work on written reports.

Preliminaries
-------------

### Admin

* I have not yet heard a revised meeting date from MICA.
* Presentations today!
* Then work on your reports!

### Questions

Reminder: Weekly Reports
------------------------

Every Sunday night each group should send a weekly report to me and
to *all* the mentors (not just yours).  The report should cover the
following four points.

* What did you accomplish during the past week?
* What do you hope to accomplish in the coming week?
* What obstacles stand in your way?
* What resources will help you accomplish your task?

Presentation Format
-------------------

We will have presentations every week.  We'll alternate between quick
presentations (this week) and more substantive presentations (next
week)

Quick

* _Intended Goals_.  Remind us of your goals for the time period and
  the points you associated with those goals.
* _Overview of Accomplishments_.  Which of those goals did you accomplish?
  What other (unexpected) things did you deal with along the way?
* _Continuing Goals_.  What are you anticipating doing in the next week
  as you wrap up this iteration?

Substantive

* _Intended Goals_.  Remind us of your goals for the time period and
  the points you associated with those goals.
* _Overview of Accomplishments_.  Which of those goals did you accomplish?
  What other (unexpected) things did you deal with along the way?
* _Demo_.  Show off the current state of your system, focusing on the
  parts you were working on.
* _Code Walkthrough_.  Show us an interesting part of your code from the
  past two weeks and explain it to us.  
* _New Goals_.  What do you intend to accomplish over the next 
  two-week iteration? What points have you assigned to each task?
  How are you dividing the work?

Please strive for organized and coherent presentations.

Time To Prepare Presentations
-----------------------------

You will have some time to work on your presentations.

Presentation: Board Bank
------------------------

### Iteration Goals

_We changed our list completely since last week._

* Review code base.
    * See below.

### Status

In reviewing code base, identified the following tasks.

* Deliver sensible error messages when you can't add a user.
  "As an administrator, I want to be able to see an error message when
   I try to add a user so that I can fix the problem."
* Fix elastic search.  Pick up where the other group left off.
  "As an organization, I want to be able to find people based on
   their indicated interests so that I can identify people who would
   actually enjoy working for my organization."
* When filling out profiles, select among interests, such as "working
  with children", or "gardening with children"
* Consider security issues.
* Look more like the GPCF Web site.  Something about green.

### Expect to complete this iteration

* Read up on Elastic search.  Complicated and essential.
* Error message.

### Questions and Answers

* Why are the error messages green?  We misspoke.
* Can I just get a list of all the volunteers?  Yes.
* Boolean searches?  No.  It depends on what the partner wants.
* Next mentor meeting: Wednesday
* Next client meeting: Needs to be set.

### Reminders for next week

* Clearly identified tasks, workers, and points.

Presentation: Phone Notification
--------------------------------

### Iteration Goals

* Check correctness of phone numbers
* Edit student information
* Get template messages working

### Status

* Phone number checking implemented!
* Student information can be edited, with some caveats.
    * But fields are not yet filled out.  Need to work on that.
    * Need a new way of changing the classroom.
    * Something about repo
* Template support
    * In progress

### Expect to complete this iteration

* Tables to deal with template stuff.
    * Reminder: Messages and translations.
    * Realize: Original database design was insufficient.  Amazingly,
      students may have multiple responsible adults.  Redesigning
      the student table first.
    * Think about changes to that table.
    * Write user stories.
    * Need to talk to community partners!
* For student information, working on filling in the fields.
* Unit tests for phone number checking.

### Questions

Presentation: GAM
-----------------

We hope that our missing group member feels better.  

### Iteration Goals

* We wanted to figure out what needed to be done on the project.
* Needed to talk to people who worked on it last semester. 
* Document code (informally)!
* Got Admin working.

### Status

* Got a good road map.
    * All the functionality is there (hah!)
    * Needs more tests.
    * Cucumber is not cool
    * Need to fix bad code
    * Need to write unit tests
    * Need to preserve Sam's credit card.
* Need to comment their code.
    * Did lots of commenting

### Expect to complete this iteration

* Talk to Alex Leach
* Establish what to do next.

Questions

* Meeting with community partner?  Not until they have specific q's.

Presentation: Resource Portal
-----------------------------

Only 60% here.  Perhaps less, because it's not clear they are at full
functioning state.

### Iteration Goals

* Understand ethics of collecting information on users
* How do we gather information from users?  Example, if someone doesn't
  have children, we don't need to show them stuff related to children.
* Talk to previous group members.
* Seed database with sample data.
* Incorporate categories and subcategories

### Status

* Need to work with MICA on ethics of collecting information
* Clients may want communication system.
* Need to consider security.
* We can now seed database.
* Categories and subcategories put on hold until we better understand
  the user paradigm.
* Need to learn how to clear database.
* Need to work on UI.

### Expect to complete this iteration

* Conceptualize UI overall.
* Revisit functionality.
* Understand security.

### Obstacles

* Talking to MICA!!!!  (Or not)

### Questions

Time to Prepare Reports
-----------------------

See above for guidelines.
