---
assigned: 2020-02-06 16:00
desc: README, Installation instructions, Acceptance Tests, GitHub Actions 
due: 2020-02-13 19:00
github_org: ucsb-cs48-w20
layout: lab
num: lab04
ready: false

---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab03/
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

# What you need to finish TONIGHT

* Conduct a standup meeting (5-10 minutes)
   
* Review your deliverables for [lab03]({{'/lab/lab03/' | relative_url }}) beyond the retrospective you held last week 
   * creating a MVP column on the Kanban board
   * tagging issues with a Github custom issue label MVP
   * tagging user story cards with `(MVP)`
   * Every team member is assigned to  **at least one issue** that is part of the MVP and that this issue is either in-progress or done
   * retro1.md documentation was logged as described on last week's lab, including definition of an experiment
   * everyone submitted a retro evaluation form   
<br/>

* Complete, or schedule a meeting for, the sprint planning (generating/updating user stories, issues) for a successful MVP delivery ONE week from tonight. Reminder: Your MVP should deliver actual value to the end user
* Decide when to hold your next retrospective and put a card for it in the TODO column
* Designate a pair of Reviewers (Lead Reviewer, Reviewer Note Taker) and a pair of Reviewees in charge (Lead Presenter and Reviewee Note Taker) from your team for next week's MVP Demonstration. Put a card with the names for these four roles in your Kanban ToDo column.  


# What you need to finish over the next week, to be demonstrated as part of your MVP release: 

To document your MVP release --- which you are delivering one weeks from today --- your repository should have a complete README.md file:

* Adapt [this README.md template](https://github.com/ucsb-cs48-w20/classMaterials/blob/master/README.md) to document your project. 

* Specifically, list and test the complete installation instructions for checking out and building your project from scratch on a new device.

* Log Acceptance Tests for your MVP user story cards

# Getting Started with Github Actions: 

* Read through and follow the steps in the [Github Actions documentation](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/getting-started-with-github-actions)
* Define and demonstrate at least one simple (but meaningful) custom workflow

   
   
<br/>   

Here's what we'll be looking for and grading:

<div class="grade" markdown="1">

**Graded**: 

* ({{page.num}}) (10 pts) Next Retrospective scheduled and put on a card in Kanban ToDo column
* ({{page.num}}) (10 pts) MVP review roles have been decided and recorded on a card in Kanban ToDo column  
* ({{page.num}}) (10 pts) Pre-MVP Sprint Planning Meeting took place and was documented in TEAM folder 
* ({{page.num}}) (30 pts) README.md file was updated for your project with
   * all the section from the template filled in (10)
   * reproducible installation instructions that let a novice user build the MVP distro from scratch, simply by following instructions (20)
* ({{page.num}}) (20 pts) Acceptance tests were authored and logged for all your MVP user stories
* ({{page.num}}) (20 pts) Github Actions: first custom workflow was created and demonstrated
</div>



