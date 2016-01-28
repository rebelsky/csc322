CSC322.01 2015F, Class 07: Iteration 1: Workshop
================================================

_Overview_

* Preliminaries.
    * Admin.
    * Upcoming Work.
    * Questions.
* Cucumber Scenarios.
* Work Time.

Preliminaries
-------------

### Admin

* Remember: You should be spending three-four hours each week outside of
  class on your project.
* Remember: You should be sending weekly reports to me and to the four
  mentors *before* each week's class.  (I think we'd all prefer them on
  Wednesday night.)
* Note: If you are bringing a client to campus, it's good to notify the
  other group that is working with that client.  (It may also be useful
  to do the same for off-campus clients.)
* What do you have scheduled today in terms of visits with mentors or
  clients?
    * Skype with mentor at 3:15
* Your first set of Cucumber scenarios (or user stories) are due today,
  as are your selection of those scenarios for working on in this sprint.  
  Do you want the first hour of class to complete that? Yes!

### Upcoming Work

* Next week: Reports/Demos to your peers.
    * What scenarios did you complete?  (If you didn't, why not?)
    * What are some interesting coding issues you encountered along 
      the way?
* Next week (and every week): Weekly report 
* I may also provide you with a more detailed project report to fill out.  

### PSA

* It's 10/10 weekend.  Please take care of yourself and those around you.
  Please know your limits.
* A paraphrased message from our Chaplain.

### Peer Events

* Blake presents today at 4:15 p.m.
* Ezra plays Saturday at 2:30 p.m. 
* Nora plays Saturday at noon.
* The Boy Who Fell From the Roof, Tonight at 7pm, Friday at 7pm, 
  Saturday at 7pm, Sunday at 2:30 pm
* Michael and Yazan's band 12:01 10/11 in Loose

### Questions

Notes on Velocity
-----------------

* One of the goals of this process is that you develop skills for estimating
  how much work your group can achieve in a given time period and also how
  much time a project will take.
* You assign a difficulty to each story.  (Fox and Patterson recommend a
  1-3 scale; Davis allowed students to choose their own scale.)
* Each iteration/sprint, you see how much you accomplished by summing
  the values of the completed stories.
* This sum is your *velocity*.
* We don't compare teams by velocity; each team gets to choose its own
  scale.
* But we hope that your velocity is consistent from week to week.
* As you get better at estimating, you'll find that your velocity
  stays relatively consistent.
    * What was a 3 story at the beginning of the semester may be a 
      1 story at the end of the semester
* Given a new project with a list of stories, you should be able to give
  a moderately good estimate of the total time required by estimating the
  difficulty of each story and dividing by the velocity.

Cucumber Features
-----------------

### Grants

### Notifications

        As an administrator
        I want to be able to set the texting service the Gem uses
        So that I can change who pays for it

        Scenario: Make SamR's account the working account

          When I go to the configure page
          And I click on "Text Service"
          And I enter rebelsky@grinnell.edu
          And I send a text
          Then it is billed to rebelsky@grinnell.edu

### Board Bank

### Resource Guide

Work Time
---------

