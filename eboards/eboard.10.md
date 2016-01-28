CSC322.01 2015F, Class 10: Iteration 2: Demos
=============================================

_Overview_

* Preliminaries.
    * Admin.
    * Questions.
* Presentations.
    * Resource Portal.
    * Board Bank.
    * Robotexter.
    * GAMT
* Open Work Time.

Preliminaries
-------------

### Admin

* Your final time will be used for your final presentations.
* Your grade in this class will depend on
    * Your final portfolios - individual and group (instructions around
      Thanksgiving)
    * Your participation and attendance in class.
    * Some assessment of bi-weekly presentations.

### Questions

Resource Portal

* Requires most of the fields on entering things.
* Playing with CSS to get new appearances.
* Need to add a login system.
* No cucumber tests.
* Sorting.
* Maybe filtering.
* Long-term: Nearest to us.
* What challenges did you run into?
    * How do we make fields required?
    * Storing data in a database.  Thanks Marcel.
* Michael: How did you use Bootstrap?  A challenge
    * Using a HAML format for Bootstrap.
* Larry: How is Bootstrap working.
* Lots of copy and paste and "look, it works".
* Emma: What's your workflow? Git trunk!

Board Bank

* Goal: Connect non-profit organizations with people who are interested
  with serving them.
* Two-way connections.
* They are doing the searches right now using elastic search
* They get approximate matches (yay elasatic search).
* Which columns.
* Getting elastic search to work right was a bit of a challenge.
* Albert: How hard was it?
    * A bit complicated.
* Albert: Why elastic search?
    * Works with Heroku
    * Lots of people use it.
* They have a not-found case.
* Ezra: What were your cucumber scenarios?  What were your challenges?
* Ezra: Have you pushed to Heroku?

Timely Notifications

* Goal: Sending messages to student parents.
* They want it asap.
* Privacy laws suggest that teachers should only see the students in their
  classroom.
* They added a classroom field to the teachers table.
* Turned out to be more cmoplex than they thought.
* Migration is built, but it's not working.
* Use Twillio to get this work.
* David: It looks like anyone can add classrooms?
* Abraham: Should we have multiple parents?
* Discuss with client: How many entries per student?
* Larry: WHo is bankrolling the sending.
* Challenges?
    * Migrating tables.
    * Figuring out the database structure.
    * Better correspondence of things.
    * Figuring out more of the SQL.

GrantApp

* Worried about edge cases this week.
* Doing a nice job of moving from use cases
* Need to improve UI.
* Zhi: HOw did you de
