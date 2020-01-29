---
assigned: 2020-01-30 16:00
desc: First Team Retrospective
due: 2020-02-06 19:00
github_org: ucsb-cs48-w20
layout: lab
num: lab03
ready: true

---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab04/
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

<div class="grade" markdown="1">

**Graded**: ({{page.num}}-I) (20 pts) You earn these individual points if you participated in tonights retrospective.

**Graded**: ({{page.num}}-I) (20 pts) You earn these points for submitting feedback on tonights retro via a Google Form survey.
(See the General channel on the [ucsb-cs48-w19 Slack Channel](https://ucsb-cs48-w18.slack.com) for the link; to avoid spam entries, we aren't posting the link on the public facing website.)

**Graded**: ({{page.num}}-T) (30 pts) You earn these team points based on the attendance/participation in your retrospective; 10 per team member for
teams of 6, 12 per team member for teams of 5.

**Graded**: ({{page.num}}-T) (30 pts) You earn these team points based on producing an artifact from the retro indicating the team's experiment:
what are you changing, what improvement do you hope for, and how will you measure whether you got that improvement?

See below for instructions on where to record this artifact.

</div>


# Recording your team's retro artifact

It might be convenient to store the team's retrospective artifacts in one of our existing places (e.g. under the team directory of the repo, or on the team repo's wiki).

However, there is a sense in which a team's retrospective artifacts should really be private to the team itself.  

It will also help the instructional staff to have a consistent naming convention so that we can locate your retro artifacts for course grading purposes.

## Create private `team-name_RETROS` repo

Accordingly, the team should please create a **private* repo with the name as indicated below.  
* The retro leader should take responsibility for making sure this happens, but...
* It is totally appropriate to delegate the actual creation to another member of the team 
* It is helpful if this happens *before* the class meeting where the retro is scheduled.

First thing: go to <https://github.com/{{page.github_org}}> and create a new **private* repo with your teams name followed by the suffix `_RETROS`

| For team | create repo | with link    |
|----------|-------------|--------------|
| `4pm-stock-trading` | `4pm-stock-trading_RETROS` | [4pm-stock-trading_RETROS](https://github.com/{{page.github_org}}/4pm-stock-trading_RETROS) |
| `5pm-pet-life` | `5pm-pet-life_RETROS` | [5pm-pet-life_RETROS](https://github.com/{{page.github_org}}/5pm-pet-life_RETROS) |

etc...

Create it as follows:
* private
* with a `README.md`
* no `.gitignore` and no `LICENSE`  needed

Then, add each of the team members to that repo as collaborators, by their github id, as `admin` level collaborators.

It is not necessary to add your mentor, TA or instructor&mdash;we have access automatically since the repo is created under the github `{{page.github_org}}` organization.

# Recording the artifact

Make a file called `retro1.md` in the repo.

## Required

In the file:
* Record who led the retro
* Record the list of which team members participated in the retro
* Record the *EXPERIMENT* that your team will undertake as a result of this retro
   * Something your team will do differently
   * What result you hope to get 
   * How you will measure whether you got that result

## Optional

* Record anything else you think the team might want to remember from this retro


# Over the next week: MVP Planning

To help your team (as well as your instructional staff) know what you are defining as part of your MVP---which you are delivering two weeks from today
, we are asking you to do things process/tool wise:

* Create a new column on your Kanban board.  
   * Call it MVP, and put everything (in terms of user stories and issues) from the TODO column that is part of MVP into that column.
   * Leave everything that is NOT part of MVP in the TODO column.
   
In addition, issues on Github can have labels.  Github creates some predefined labels, but can edit these and add new ones.

* Add a new label called MVP.
   * Add that label to all of the issues that are in the MVP column, as well as any issues that are already in-progress or done
      that are part of your MVP.
 
Finally, while regular cards cannot be given "labels" in the same way that issues are, you can just use the letters `(MVP)` in parens
as a kind of label on the user stories that are part of your MVP.

In this way, anyone can look at your Kanban board, and see:
* What is, and what is not part of your MVP
* Which user stories and issues are still not started, in progress, or done, with respect to your MVP.

# Deliverables and Grading for {{page.num}}

By the end of due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}), you should be halfway done
with delivering a significant number of issues towards your MVP.

Here's what we'll be looking for and grading:

<div class="grade" markdown="1">

**Graded ({{page.num}}-I)**: (20 pts) towards the individual part of your grade for {{page.num}}.   We will be looking to see that you (as an individual)
are assigned to **at least one issue** that is part of the MVP and that this issue 
is either in-progress or done by {{page.due |  date: "%a, %b %d at %l:%M%p"}}).

**Graded**: ({{page.num}}-I) (20 pts) towards the individual part of your grade for {{page.num}}.   You earn these points if/when you, by the due date of this assignment (i.e. {{page.due |  date: "%a, %b %d at %l:%M%p"}}):

* The issue/issues to which you are assigned have comments on them with a link to the branch or fork where you are working on the issue.
* There is evidence of some commit activity showing progress towards the goal
* There is a discussion in the comments on the issue indicating the progress you are making.  This may include questions, or some boxes on a check
   off list being checked, etc.

</div>


<div class="grade" markdown="1">

**Graded ({{page.num}}-T)**: (30 pts) towards the team part of your grade for {{page.num}}.  

As part of this grade, each team member 
should be assigned to  **at least one issue** that is part of the MVP and that this issue 
is either in-progress or done by {{page.due |  date: "%a, %b %d at %l:%M%p"}}).

For teams of 6, this part of your grade is 5 points per team member.  For teams of 5, it is 6 points per team member. For teams of 7, it is 4.28 points per team member.   

These points are all or nothing; if you've made a reasonable attempt, even if you didn't earn 100% on the individual portion, 
your team will earn the points for your contribution towards the whole.  

The most important learning goal of the course is to learn to work as a team, supporting one another, and building the team's success.

</div>  

<div class="grade" markdown="1">

**Graded ({{page.num}}-T)**: (30 pts) towards the team part of your grade for {{page.num}}.  

This part of the team grade is for the mechanics of:
* creating a MVP column on the Kanban board
* tagging issues with a Github custom issue label MVP
* tagging user story cards with `(MVP)`
</div>  

