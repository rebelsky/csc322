CSC322.01 2016S, Class 04: Sprint 1, Week 1
===========================================

_Overview_

* Preliminaries.
    * Admin.
    * Upcoming Work.
    * Extra Credit.
    * Questions.
* Presentations
* Form
* Group Work Time

Preliminaries
-------------

### Admin

* Sam is leaving early to meet with the visitor

### Good things

* Reception with Hilary
* Hilary Talk
* Swimming!  (Diving at 1pm tomorrow and Saturday)
* Basketball 3:00 p.m. Saturday
* Lunar New Year 5:40 Saturday, free food (to you)
* Submit to the sequence, Grinnell's incredible sequential art publication
* Submit to vantage point, which focuses on accessibility and disability
* Next week's Town Hall
* Include more details in your reports.

Presentations
-------------

Goals

* 5 important user stories
* 1-3 goals for this week (preferably as user stories)
* anything else from/for the broader classroom

Next week

* What you accomplished
* Demos!
* What went wrong

### Notifications

#### Notes

* "We are close to our first release.  So we are focusing more on 
  bug fixes and such."
* "We didn't understand that pair programming is a key part of agile 
  development.  We'll do MUCH better next time."

#### Stories

* "As an open source contributor, I want to be able to actually look
  at the code and understand what it does." - Done  (4)
* "As a teacher, I want to be able to send messages to entire classrooms 
  easily so that I can have more time to do other things."  (3)
* "As a developer, I need tests in place so that I can be sure that the
  system I am deploying works."  (Goal write and implement.)  (8)
* "As a user, I want to be able to see all the texts that have been
  sent so that we don't waste people's time or resources." (8)

#### Plan to Implement

* Everything (23 points)

#### Questions from the Class

_How did you determine the points for each task?_

> WAG!

_What service did you integrate?_

> Travis!  `travis-ci.org`

### Board Bank

#### User Stories

* "As a student in this class, I want a working codebase so that I
  can actualy do something."
* "As a user, I want to be able to enter and update my profile information
  so that organizations can find me based on my skills." (5)
* "As a GPCF employee, I want to be able to see appropriate branding so
  that it is clear that this is associated with GPCF." (6)
* "As a user, I want to be able to volunteer for other kinds of
  activities, too, so that I can be placed with the correct organization
  and thereby better support my community." (6)
* "As an organization, I want to be able to filter the employees by
  skill set so that I can narrow my deeper search to the employees
  more relevant to the position." (8.25)
* "As a board bank admin, I want to be able to approve organizations so
  that no fradulant organizations (like StuACM) can access the Web site." (5)

#### Focus

* Get to ground level. (many)
* Write more tests.
* Gather last semesters students and lock them in a room until it passes
  the tests.
* UI work.

#### Questions

_How do you decide what skills people can list?_

> Legacy code.  We will check the list with GPCF.

> Also an open reponse field.

_Once you get your application to look right, will you fix ours too?_

> We can collaborate.

_Do your tests just fail on Travis, or everywhere?_

> Boom.  Crash.  We will be discussing these issues with the previous
  group(s).

### Resource Puddle

#### Stories

* "As a normal user, I should not be able to change things on the Web site
  so that I don't screw things up or provide inaccurate information."
     * 1 point approach: No non-admin login allowed.
* "As an administrator, I want to limit what things other users can change
  so that I can be sure that our information is reliable."
* "As an administrator, I want to be able to make trusted people administrators
  so that others can update information."
* "As a community member, I want to be able to access the Web site on a
  24-7 basis so that I can be assured of getting the resources I need when
  I need them." (aka upload to Heroku)
* "As an administrator, I want to be able to use a certificate so that
  people can access the site over SSL."
* "As a community member, I want to be able to find a service by entering
  the name of the service (or by typing a similar name) so that I can
  be connected to a service I already know about."

#### Goals

* Fix the checkboxes [1 point]

#### Questions

* None

### Grant Application Manager

#### Stories

* Specific one, related to UX: "When I'm a user and I'm signed in and return
  to the front page, I should not see the 'sign in' button." (1.5)
* "As a user, when I submit an application, I should get an email confirmation
  that it is successfully submitted."  (5, but we don't know how hard email
  is)
* "As a team, we want to assign tasks so that we can accomplish tasks in
  parallel." (.5)
* "As a developer, we want unit tests ready for our code." (10)
* "As devevelopers, we want to integrate Travis so that we know how much
  area is under Travis." (4)
* "As a reviewer I want to rate and comment on applications so that
  they can be compared." (6)

#### Goals

* UX
* Rate and Comment
* Tests
