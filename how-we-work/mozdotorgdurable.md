# Mozilla.org Durable Team Workflow Overview

## Workflow Overview

For an in-depth look at how Mozilla.org gets stuff done please see this [presentation](https://docs.google.com/presentation/d/1p4PLfoEZW8OVoBT1ZBVu4NOOz6WUeqySpnWaeNrAVTQ/edit#slide=id.g2b28aa21b3_2_585). What follows are some basics about how work flows through the team and details about
how we use Github.

### Work Intake

Work requests come into the Mozilla.org durable team from both durable and functional teams from across MoCo & MoFo. Non trivial or project work usually results in a Brief submitted to David Tenser for vetting and approval. Projects are prioritized according to an established [model](https://docs.google.com/presentation/d/1MnxtGiPuYZ1KxFY-KM-NQh7VFlaysJp7gB4rBkJyFXo/edit). 



### Approval Process

This depends on the type of work (which bucket and the Accountable person identified in the RASCI)

Simple work requests are evaluated by the PM and an appropriate team member based on the ask (requirements) and the work is entered into Github.

Complex work (brief required), once approved by SLTs, comes to the team and is distributed for review in advance of the kickoff meeting that occurs to initiate the project.

When the Team Lead approves the work at hand it is then reviewed by the Accountable/Approver identified in the RASCI for approval.  When approval is given the team finalizes the work and takes it live asap or on the specified delivery date.


## Github

Our team manages it's work via Github. Our goals with this process are:

- Prioritize and assign work in a fair and balanced way.
- Communicate status within the Moz.org and the larger Marketing organization.
- Identify risks, blockers and high priority issues.
- Foster collaboration.

Whenever possible our work should be public and discussed openly in github issues. When tasks contain sensitive data
or can not be public, please track work in private bugzilla issues.


## Github Overview

Moz.org maintains a *[Project Board](https://github.com/mozilla/bedrock/projects/3)* that shows an overview of all the significant projects, tasks and their status. Details about each project can be found in the card. Work & tasks for these projects are tracked on separate project specific boards. Work that is too small to qualify as a project (for example, text updates to the leadership page) should still be represented on this board. If there are multiple tasks but the work is still not a project, group using references to keep the board tidy.

```
└── Project Board
    ├── Project #1 Board
    ├── Project #2 Board
    ├── Project #3 Board
    └── Project #4 Board
```

### Project Board & Projects

Significant projects are tracked on our [Project Board](https://github.com/mozilla/bedrock/projects/3).

Rules for this board are as follows:

1. Any significant project (defined as work containing multiple tasks with multiple people) must have a card on the board.
1. The project on the board must have a description containing links to any background information and that projects task board. 
1. Keep the contents of these cards limited, discussion about actual work should occur within those tasks.
1. Only the following labels can be applied to projects:
      1. The `Project` label.
      2. The correct `Team` label. One of the following: Retention, Consumers, Firefox Growth, or Moz.org . 
      3. Blocked if blocked.
1. No other labels should be applied to projects.
1. Folks who are working on a project, should be assigned.

#### Project Board Columns

- `Icebox` - Projects that have been prioritized to occur next.
- `Ready` - Prioritized projects that are ready to start.
- `In Progress` - Projects that are currently underway.
- `Done` - Shipped!

#### Moz.org Backlog & Small Tasks

For non project work or tasks too small for a project, just file an issue. The lifecycle of non-project work is as follows:

1. An issue is filed.
1. If the issue is ready to work on the label "ready" is applied.
1. If urgent, the PM or Team Lead moves it to the Project Board and either assigns someone or someone volunteers.
1. If not urgent, the work can be picked up whenever someone needs a break or has slack time.
1. Once moved to the board remove the "ready" label. 
1. If there is more than one task use a note with references to keep this tidy (see below).
1. Move the card appropriately as work progresses.

![Github References](/mozdotorgdurable/references.png)

### Project Boards

Any significant project should have it's own project board where work is managed. When work on a project is complete, the board can be closed. Nice job!

## Board Details

### What are your columns, what do the columns mean?

Generally our projects will have the following columns:

- `Backlog` - Tasks we know have to get done but are not necessarily ready to go.
- `Ready` - Prioritized tasks that are ready to start.
- `In Progress` - Tasks that are currently underway.
- `Done` - Shipped!

### How/when do cards move across the board?

Cards are moved by any member of the team when a change in status is identified. Cards should generally be moved by whomever takes the work or causes an update to status. This is not the responsibility of the Program Manager, team members show own the cards they take on including keeping the status up to date.

## Labels

We use a lot of labels, below are some special ones:

- `Blocked` - Tasks that can not move forward and require some action to get moving. 
- `Needs Review` - Tasks that need review (creative/pr etc) to move forward. 
- `Fire` -  Urgent request that should take priority over other work. This could be work that has legal, financial or firefox download ramifications. Fire requests should always be vetted with the Team Lead to determine priority.
- `Ready` - A task has all the information required for work to start, and can be picked up at any time.
- `Project` - Should only be used for cards on the Project Board.
- _* Team_ -  Should only be used for cards on the Project Board.


## Daily Standups

*How / when to stand ups occur, what happens during a meeting, be brief!*

* Stand up & Status - Mondays at 9-9:30 am PT - Stand up followed by project status review 
* Stand ups - Tuesdays & Thursdays at 9-9:15 am PT
* Team time - Wednesdays at 9:15-10 am PT - recurring, non-required meeting where we attempt realize the benefits of colocation (as we are not colocated)


## Retrospectives

Team Retrospectives are held every three weeks. These are 'team only' meetings, defined as safe spaces in which candid commentary is allowed and expected with the intent learn from previous circumstances
We focus on: 
- Did we follow up on Action Items from last retrospective?
- What do we keep doing?
- What could use improvements?
- What do we stop doing?
