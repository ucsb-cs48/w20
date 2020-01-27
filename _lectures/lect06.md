---
desc: Minimum Viable Product
lecture_date: 2020-01-27 14:00
num: lect06
ready: false

---


Topics: 
* Announcements: Reminder: Logging meetings in GitHub, Retrospective in Thu Lab (lab03: <https://ucsb-cs48.github.io/w20/lab/lab03/>)
* Looking ahead: [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product)
* README.md template <https://github.com/ucsb-cs48-w20/cs48_agile/blob/master/sample_README.md> for your project
* Class standup and other Scrum coordination (Sprint02).
* Software Development Process (cont.): evolutionary, agile/extreme programming

# Choose the right size MVP!

<div style="font-size: 150%; width: 35em; margin-left:auto; margin-right:auto; background-color: #fef; border: 4px solid red; padding:1em;" markdown="1">
* If it doesn't deliver value ⇒ too small
* If you can't finish by due date ⇒ too big
</div>

# MVP Planning

To help your team (as well as your instructional staff) know what you are defining as part of your MVP---which you are delivering two weeks from today
, we are asking you to do things process/tool wise:

* Create a new column on your Kanban board.  
   * Call it MVP, and put everything (in terms of user stories and issues) from the TODO column that is part of MVP into that column.
   * Leave everything that is NOT part of MVP in the TODO column.
   
In addition, issues on Github can have tags.  Github creates some predefined tags, but can edit these and add new ones.

* Add a new tag called MVP.
   * Add that tag to all of the issues that are in the MVP column, as well as any issues that are already in-progress or done
      that are part of your MVP.
 
Finally, while regular cards cannot be given "tags" in the same way that issues are, you can just use the letters `(MVP)` in parens
as a kind of tag on the user stories that are part of your MVP.

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

For teams of 6, this part of your grade is 5 points per team member.  For teams of 6, it is 12 points per team member.  

These points are all or nothing; if you've made a reasonable attempt, even if you didn't earn 100% on the individual portion, 
your team will earn the points for your contribution towards the whole.  

The most important learning goal of the course is to learn to work as a team, supporting one another, and building the team's success.

</div>  

<div class="grade" markdown="1">

**Graded ({{page.num}}-T)**: (30 pts) towards the team part of your grade for {{page.num}}.  

This part of the team grade is for the mechanics of:
* naming a retro leader for the lab04 retro and putting a card in the TODO column with their name
* creating a MVP column on the Kanban board
* tagging issues with a Github custom issue tag MVP
* tagging user story cards with `(MVP)`
</div>  

You main task tonight is to adjust the user stories and issues that you want to include in the MVP.

There is more detail on how to do that below.


# Class slides: 
We covered the following:
<https://sites.cs.ucsb.edu/~holl/CS48/handouts/Slides_SWDevelopment.pdf>

# Electronic Handouts:
* Markdown tutorial: <https://commonmark.org/help/>
* Minimum Viable Product: <https://en.wikipedia.org/wiki/Minimum_viable_product>
* Hierarchy of Needs: <https://sites.cs.ucsb.edu/~holl/CS48/handouts/HierarchyOfNeeds.pdf> 
	
	
# Background Information: Code Smells
* Code Smells: <https://blog.codinghorror.com/code-smells/>
* Unmaintainable Code (humor): <https://github.com/Droogans/unmaintainable-code>