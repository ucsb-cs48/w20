---
assigned: 2020-01-30 16:00
desc: Deliver MVP
due: 2020-02-13 19:00
github_org: ucsb-cs48-w20
layout: lab
num: lab05
ready: true

---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab05/
</div>

<style>
div.grade { margin: 2em; padding: 1em; border: 2px solid #0c0; background-color: #efe; }   
</style>

<div style="float:right; width: auto;">

<table style="margin-top:1em;">
<tr>
   <th>Points</th>
</tr>
<tr>
   <td class="pointCount"></td>
</tr>
</table>

</div>
<BR/>


This lab will be all about delivering your Minimum Viable Product. This will give you the opportunity to get early feedback from your mentors, the TAs and instructor, and from your peers. We put into place a process in which every team designates a set of representatives to evaluate a peer team's MVP. Please take the following guidelines into account: 

In the [previous lab]({{'/lab/lab04/' | relative_url }}), every team designated a pair of Reviewers (Lead Reviewer, Reviewer Note Taker) and a pair of Reviewees in charge (Lead Presenter and Reviewee Note Taker). The other people from every team team stay with their Lead Presenter and Reviewee Note Taker and will help with the presentation. 
The following table shows the reviewer-reviewee assignments:       

| **Reviewers from this team:**  | **... will review this team's MVP:** |
| 4pm-MsgOrg ------------------> | 4pm-LaptopComparison |
| 4pm-LaptopComparison --> | 4pm-Tree |
| 4pm-Tree ------------------------> | 4pm-Synth | 
| 4pm-Synth --------------------> | 4pm-GPS |
| 4pm-GPS ----------------------> | 4pm-MsgOrg | 
| | |
| 5pm-Rideshare --------------> | 5pm-Discord | 
| 5pm-Discord ------------------> | 5pm-Sched | 
| 5pm-Sched --------------------> | 5pm-Game | 
| 5pm-Game ---------------------> | 5pm-Restroom | 
| 5pm-Restroom --------------->   | 5pm-Rideshare | 
| | | 
| 6pm-Climb ----------------------> | 6pm-Gauchoshare | 
| 6pm-Gauchoshare ------------>   | 6pm-Housing |
| 6pm-Housing ------------------> | 6pm-Spotify | 
| 6pm-Spotify ----------------------> | 6pm-Climb |


#  The most helpful attitude and approach for reviewers: friendly helpfulness, not "gotcha"

First, it is important to have the right approach.  You are engaging in this review to *help the other team improve their code*.  This is not an opportunity for showing off or playing "gotcha".  

On the other hand, don't hold back on sharing what you find.  The grade for this review is not based on how well team B's product performs.  It is based on how much team A is helpful to team B.     

Everything you find that can be perceived as a weakness in team B's product is something that you can help them uncover early, so that they can address it while they still have time, long before the end of the quarter.

Don't mock or criticize---be helpful and constructive.   If you have knowledge of a practice or technique that can help another team, make a note of that, and come back and share it later (e.g. on the slack).

# The most helpful attitude for reviewees: gratitude, not defensiveness.

For reviewees, it can be really tough to be out front representing your team as another team's representative goes through your product inside and out.  There is a natural human tendency to become defensive.

It may be helpful to resist this urge.

## What if we disagree with the reviewer's assesssment?

That's ok.  It's ok to just nod and let it go.

* You do NOT necessarily act on every piece of information or suggestion you receive from the reviewers.  
* Your team may not agree with all of it.  
* Your team has every right to decide, if they judge the advice or suggestions to be incorrect or unwise, to let them go.  It isn't necessary to argue back with the reviewer. 

All I'm asking of you is to listen and consider it carefully, and discuss it as a team.  You might decide to discuss it later after the review is over, on the Slack channel.  With a bit of distance in space and time, you may find parts of it you agree with, or really good reasons to go in a different direction from what was suggested. You will document your decisions. 

# Instructions for Reviewers

As the reviewer, you are from team A, and reviewing the work of team B.

Present, there should be:
* You, lead reviewer from team A
* Someone from team A to take notes on the Slack
* Lead reviewee from team B
* Someone from team B to take notes on the Slack
* The mentor for team B.

1.  Start by making sure that you and your helper from team A are added to the slack for team B. Also, the lead reviewer will have to be (at least temporarily) added to the repo, if it is private (for Steps 4 and 5 below).


2.  On the slack, make a note of everyone present at the review from both teams.  Any members of team B that are missing hopefully are missing because they are engaged in the review  of another group's product.
    
2.  Then, start by sitting around the computer that team B's lead presenter chose to demo the product. The lead presenter from team B has the product up and running.

3.  Ask the lead presenter to walk you through the features of the product, as YOU, leader reviewer from team A, control the mouse and keyboard or tablet/phone touchscreen.  You, the lead reviewer should be going through the features of the product, led by an explanation from the team B presenter.  

    As you notice things you like, and things that could be improved, say them out loud.  Both, the Scribe from team A and the Scribe from team B should be noting these things on the Slack.   The Scribe from team A should simply make notes about your observations.  The Scribe from team B may go a step further, and note what the team might do in response (e.g. add issues, add user stories, add bug fixes, etc.)
    
4.  When you have gone through the product demo, now go to your OWN computer.   Pull up the Kanban board.

    Go through all of the user stories and issues that you see that are marked as part of MVP in in-progress or done. 
    
    Comment on whatever you see that either in-line with what you experienced in the demo, out out of alignment, in your view as a potential user of the product.  Again, the notetakers should make notes as they did in earlier steps.
    
5.  Now, pull up the README.md for the project in the repo.

    Go through it and make sure it doesn't have any "TODO" items in it.  If it does, comment on those, and note that they should perhaps be addressed.  
    
    Finally, on your OWN computer, try to clone the repo, and follow the steps needed to get the application up and running. 
    
    You should NOT need any additional credentials from the original team---if there is a database setup needed, you should BE ABLE TO DO THAT DATABASE SET UP YOURSELF by following the instructions in the README.md.  If that is not possible, then note this as one of the observations.    At any point that you are stuck and cannot continue, as a last resort, the reviewee can jump in and help, by guiding you through the process, but NOT by providing you database credentials or API credentials--only by walking you through the process of setting up your own.
    
6.  [OPTIONAL IF TIME] If you are successful in setting up the project, and you get this far: start looking through the code for places you can make suggestions for improvement, or offer words of praise.  Most reviewers won't get this far.    
    
7.  Closing the review: to close the review, try to offer a sandwich of praise and helpfulness:
   * One thing you really liked about the project (inside or outside)
   * The most impactful opportunity for improvement
   * One more thing you thought was good
   
There will be additional instructions over the next few days for consolidating this review into a summary, but for tonight this is enough.    

# Instructors for Reviewees

Read through the instructions to reviewers, since most of what you need to know is already there.

Your main job is to be at the service of the reviewer.   

# Other members of the team

For those that are not the lead reviewer or reviewee:

* At least one  member of the team should be with the ambassador of your team to the other team being reviewed as a note taker and deputy. 
* At least one other member of your team should be taking notes during the review of your team's product

The other 1 or 2 members should stay with the team being reviewed, and as notes are taken in the slack, start setting up user stories and/or issues to follow up on the items suggested, or if needed, do emergency bug fixes/edits to code or documentation to address problems found during the review.

# FOLLOW UP instructions for Reviewers

1. Please create a private github repo under the course organization {{site.org}} that follows the following naming convention, with the team name of the team that you reviewed (not your own team).   Create it with a README.md only

| 4pm-messageorg_REVIEWS | 5pm-Rideshare_REVIEWS | 6pm-Climb_REVIEWS
| 4pm-laptops-comparer_REVIEWS |  5pm-discord_REVIEWS | 6pm_gauchoshare_REVIEWS
| 4pm_tree_REVIEWS | 5pm-schedule-optimization_REVIEWS | 6pm-housing_REVIEWS
| 4pm-fmsynthesizer_REVIEWS | 5pm-game_REVIEWS | 6pm-Spotify_REVIEWS
| 4pm-GPS_REVIEWS | 5pm-restroom_REVIEWS  | 

   (You may add a .gitignore if it makes things more convenient, but its optional)
   
   Add the reviewee from the team you reviewed as a collaborator.  They will add everyone else on that team.

2. In that repo, add a file called <tt>{{page.num}}_reviewer.md</tt>. In this file, write a summary of your findings
   during the review.

   Include sections for each of the following:

   1.  Everyone that was present for the review from each of the two teams, and the roles they were in.
       You may copy this from the reviewee's report if it is already present and accurate.
   2.  A summary of the features of the product as you understood them, and what you liked or thought could be
       improved about each
   3.  A summary of what you found on the Kanban board in terms of whether the user stories and issues were, or
       were not in alignment with the features of the product.
   4.  A summary of whether the README.md was in good shape according to the criteria outlined in
       the lecture on good README.md practices, and whether you were able to follow the instructions there
       to actually set up the product to compile and run on your own computer.
   5.  Your final closing thoughts: something you liked, the most impactful opportunity for improvement,
       and one more thing you thought was good.


# FOLLOW UP instructions for Reviewees

1. If the reviewer has created the repo below, great.  If not, create it yourself, and add your reviewer as a collaborator.
   Also add everyone on your team as a collaborator.
   
| 4pm-messageorg_REVIEWS | 5pm-Rideshare_REVIEWS | 6pm-Climb_REVIEWS
| 4pm-laptops-comparer_REVIEWS |  5pm-discord_REVIEWS | 6pm_gauchoshare_REVIEWS
| 4pm_tree_REVIEWS | 5pm-schedule-optimization_REVIEWS | 6pm-housing_REVIEWS
| 4pm-fmsynthesizer_REVIEWS | 5pm-game_REVIEWS | 6pm-Spotify_REVIEWS
| 4pm-GPS_REVIEWS | 5pm-restroom_REVIEWS  | 

   (You may add a .gitignore if it makes things more convenient, but its optional)

2. In that repo, add a file called <tt>{{page.num}}_reviewee.md</tt>. In this file, write a summary of your findings
   during the review.

   Include sections for each of the following:

   1.  Everyone that was present for the review from each of the two teams, and the roles they were in.
       You may copy this from the reviewer's report if it is already present and accurate.
   2.  A response to each of the other sections of the reviewers report, including actions that you may take as a team.
       If the reviewer hasn't submitted their report yet, write a response based on the feedback you find
       on the slack channel that pertains to these items:
       
        1.  A summary of the features of the product as you understood them, and what you liked or thought could be
            improved about each
        2.  A summary of what you found on the Kanban board in terms of whether the user stories and issues were, or
            were not in alignment with the features of the product.
        3.  A summary of whether the README.md was in good shape according to the criteria outlined in
            the lecture on good README.md practices, and whether you were able to follow the instructions there
            to actually set up the product to compile and run on your own computer.
        4.  Your final closing thoughts: something you liked, the most impactful opportunity for improvement,
            and one more thing you thought was good.



<div class="grade" markdown="1">

**Graded**: ({{page.num}}) (50 pts) For Reviewer report in `_REVIEWS` repo of the partner team (not your own team's repo).
Report should contain all items indicated above.

**Graded**: ({{page.num}}) (50 pts) For Reviewee response report in `_REVIEWS` repo of your own team.  
Report should contain all items indicated above.

</div>
