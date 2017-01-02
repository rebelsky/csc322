CSC322.01 2016F, Class 23: Iteration 2: Wrapup
==============================================

_Overview_

* Preliminaries.
    * Admin.
    * Upcoming Work.
    * Extra Credit.
    * Questions.
* Reminder: Presentation components.
* Presentation prep.
* Presentations.
* Work time.

Preliminaries
-------------

### Admin

* Welcome back from break!
* It's time for a new iteration.
* Don't forget that your reports were due last night.
* For this half of the semester, we will meet for six hours per week.  
  That's about the right amount of time to spend per week on a 2-credit,
  full-semester course.  So you shouldn't worry too much about trying
  to do work outside of class.

### Questions

Presentation Format
-------------------

Yup, it's a "big" presentation day.

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
* _Extra Questions_.  Do you think you'll be finished by the end of 
  the semester?  Do you also want to start a second project?

Please strive for organized and coherent presentations.

Time To Prepare Presentations
-----------------------------

Particularly since we're just getting back from break you will have some 
time to work on your presentations.

Presentations
-------------

### Text Messaging (aka "Head Start Notification")

Intentions: Map out tables.  Learn Twilio.

Accomplishments: Map out tables (1).  Did research on Twilio (4).  

Velocity: 5.

Notes on Twilio: 

* Twilio sends data to a URL.
* They aren't sure about the URL.
* Sends lots of parameters.

Demo: (Sorry; nothing new.)

Plans: Implement tables (4 points).  Implement forwarding one text message
(5 points).

Questions: 

* Will you finish?  It depends on how hard Twilio is.  Probably not.
* Explain your architecture.  See whiteboard.

### Resource Portal

Intentions/Accomplishments:

* Tagging
* Elastic search (2 points)
* Unique resource validation (2 points)
* Splash page and menu (5 points)
* Testing (2 points)
* Seeding the database (we'd done that). (1)

Notes:

* Tagging tutorial didn't quite work.
* May rollback.
* Whoops!  Eliminating categories broke lots of things.
* Clarificiation: They made progress on things, as opposed to finishing
  them.

Plans (a lot is related to tagging):

* Need to test admin validation and merge in to codebase. (4)
* How to display tags. (4)
* Splash page and link up with rest of team. (5)
* Small tagging things (nx2).
    * Fixing views.
    * User controller refactoring.
    * Weird database migration issue.

Discussion:

* For the UI: They want to do autocomplete/suggestion type stuff.
  Question: Wouldn't a menu of key categories be better?

Question:

* What did you do with elastic search?  Needed to rebase and start
  and maybe add a few gems.

### Grant Application Management (aka "The other group")

Intentions

* Two teams: One doing RSpec, one doing UX.
* UX: Figure out how to upload applications (1)
* UX: Enumerate admin capabilities (3)
* UX: Check if files are visible (1)
* UX: Enumerate user capabilities (3)
* RSpec: Read through documentation (3)
* RSpec: Found one test (1)
* RSpec: Go through Tutorial (5 ; to be continued)

Velocity: About 17

Demo:

* Look!  We can upload things.

RSpec code walkthrough

* Note: Need to write

Next iteration:

* RSpec: Finish going through tutorial (5)
* UX: Teach others (4)
* Talking to mentor on Wednesday.  Need to talk to them about how to
  divide the big tasks.
* Want to add a program manager.  
* RSpec: Revisit iteration steps (2)
* RSpec: Enumerate features to be tested by RSpec (5)
* ??: Review users (2)
* ??: Enumerate more things (4).

### Board Bank

Intentions:

Accomplishments:

* Can verify phone numbers (that they are the right form) (3)
    * It's obnoxious, but EZ says "You sometimes have to be obnoxious to get things done."
* Tried to replicate code for skills into interests.  (4) Didn't quite
  finish.  Need to update database table.
* Six points.

Planned

* Finish interests (3-4; we mis-estimated).
* Improve interface 
   * add a "view organizations" [1]
   * return to login [1]
   * add logo [1]
   * reject offer [4]
* Learn more about ActiveAdmin and ElasticSearch (2)
