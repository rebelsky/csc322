CSC322.01 2015F, Class 09: Iteration 2A: Workshop
=================================================

_Overview_

* Preliminaries.
    * Admin.
* Quick check-ins.
* Longer check-ins.
* Cucumber scenarios.
* Work time.

Preliminaries
-------------

### Admin

* Food-like substance of the week!
* EE plays at 3:30pm today, LG plays at 7pm, NBB and EE play on Saturday.
* Don't forget the cool CS Extra today.
* I will need to leave at about 3:25 today for an unplanned appointment
  that couldn't be changed.
* I am likely to include comments in today's eboards about your work and
  presentations.
* Interesting news: One of the Grinnell prize winners needs software
  written ....

### Questions

Quick check-ins
---------------

* When are you next meeting with your mentor?
* When are you next meeting with your client?

Grant board: 5pm on Sunday; Client knows that they should meet.  EG can drive.

Resource portal: Next week; Client after they make more progress.  Deciding
on which client to meet with.

Notification system: Arranging times.  Needs to have it working before
meeting with clients.  Jamie next, then Head Start.

Board bank: Cassie next week.  Client week after.

Longer check-ins
----------------

Notification system: Demo failed.  Database broken.  Database now
fixed.  Added some fields to user model.  Works with new users page.

Board bank: Objective had been to get search working.  But the Gem
wouldn't work.  Working with Gems is fun.  And rewarding.  And now it
works after lots of thrashing.  Turns out that it needs more than the
Gem; you also need other files.  Elastic search seems to work on Heroku
using the Banzai add on.

Grant App: Can upload application forms and rubrics.  Can download application
forms and rubrics.  Doesn't break if forms/rubrics are missing.  Reviewers
can download files.  Applicants can upload files.

Resource Portal: Last week tried to show the Web site.  Failed.  But now
it works.  They will show us *next* week.

Cucumber scenarios
------------------

Resource portal:

* Old: "Hey let's have a Website that works."  Now works.
* As someone who knows about resources, I want to be able to enter those
  resources into the system so that members of the community can use them.
* As a single mother who needs food for her children, I would like information
  about food resources in the area so that I can feed my family.
* As people who are in charge, we would like to approve any resource before
  it is added.

Grant app:

* Observation: Cucumber scenarios are hard to write with file uploads.
* As a developer, I want to write cucumber scenarios that deal with file
  uploads, so that I can test my code.  (I will ask Alex.)
* As an administrator, I want to be able to submit grants that were turned
  in on paper so that they can be reviewed with the other grants.
  (As an administrator, I want to be able to pretend to be an applicant
  so that I can upload applications under that person's name.)

Notification team

* As a teacher, when I ask for a list of students, I should only see the
  students in my classroom.

Board bank

* As a user I want to be able to search for an information by name so that
  I can learn more about the organization.
* As an organization, I want to be able to search for a user by name so that
  I can learn more about the user.

Work time
---------

