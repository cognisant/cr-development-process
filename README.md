# Cognisant Software Development Process

Cognisant develops software products for several companies. It uses the [Scrum](<https://en.wikipedia.org/wiki/Scrum_(software_development)>) framework, with development work arranged in two-week [sprints](<https://en.wikipedia.org/wiki/Scrum_(software_development)#Sprint>). Together, Cognisant and its customers define what development work goes into each sprint. This guide describes how that process works.

## Process

### Discovery

Users can add cards to the **Software Development** Trello board using a web form, hosted internally on the Intranet. This form asks users to provide:

- A title
- A description
- A proposed solution (optional)
- The impact on the business

When a user submits information using this form, a card is created in the **Inbox** list on the **Software Development** Trello board containing all the information they provided, along with their name and email address.

The team may also manually add cards to Trello at the request of management. When this happens, cards should follow the same format as above.

### Triage

From time to time, the team will go through all the cards in the **Inbox** list on the **Software Development** Trello board, and determine whether or not the idea adds value.

If it does, it gets moved to the **Idea Backlog** list. Otherwise, a comment is left on the card explaining the decision, and the card is archived.

The team may need to consult the user to determine whether the idea adds value. Any discussion or clarifications should added to the Trello card for future reference.

### Prioritisation

### Research

#### Writing Stories

#### UI Mockups

#### Business Review

Before a story can be worked on, the business member who submitted the original Trello card, or another relevant member of the business, must approve the story.  
This ensures that the story accurately describes the original problem, and includes acceptance criteria for an appropriate solution.  
Simplisitc stories, such as bug descriptions, do not require a business review.

Sometimes the team will have envisaged a solution to the problem, which is significantly different from the solution originally suggested by the member of the business.  
In these instances, a more in-depth discussion may be necessary to explain the story to the member of the business.

If the business member is not happy with the story, the team will rewrite the story to address their concerns.

#### Definition of Ready

### Estimating Effort

### Sprints

#### Sprint Kick-off

#### Selecting Stories

#### Generating Tasks

#### Daily Scrums

#### Definition of Done

#### Demos

On the last day of a sprint, the team meets with relevant members of the business to present them the work the team completed during the sprint.

The demo is an opportunity for the business to provide feedback on the work.  
Often, any small problems the business points out can be corrected before the end of the day.

This meeting is also a chance for the team to explain how the completed work applies to the business' short term goals.

There is usually a discussion about when the work might be deployed to production and become accessible to users.

#### Retrospective

On the last day of a sprint, after the demo, the team has a retrospective meeting.

Members of the team take it in turns to bring snacks for the whole team to this meeting.

During the retrospective, the team discusses how the sprint went, reflecting on what went well during the sprint, any issues that came up, and how productive the sprint was.

The main objective of these meetings is to identify improvements that could be made to the development process.

During the sprint, the team uses the Retrospective Trello board to record any points they think should be discussed at the retrospective.  
At the meeting, the team will review all of the discussion points added to the board.  
If necessary, the team will attempt to think of a systematic method of addressing a point raised.  
Often discussion points are simply something to keep in mind during future sprints, or a small problem that can be immediately addressed with a simple action.

Any possible process improvements agreed upon by the team will be trialled in a future sprint, then discussed and refined during that sprint's retrospective.

An example of a process improvement derived from a retrospective meeting is [the work in progress limit](https://github.com/cognisant/Docs.DevelopmentProcess/blob/dev-with-retrospective/docs/work-in-progress-limit.md).

## Tools

### 1Password

1Password is the password manager the team uses to securely store and share work-related passwords.

Team members use private vaults to manage passwords for their own work-related accounts.

There is also customer-specific vaults. These are used for managing shared credentials associated with a specific customer, or a software system used by that customer.

If a team member needs to use the credentials of a shared account, they can find them in the relevant vault.

### Planning Poker Cards

### Slack

### Sprint Board

The development team has a large, physical whiteboard in their workspace called the _sprint board_. The sprint board has three main sections, each used to track a different aspect of the sprint.

#### Sprint Progress Columns

Kanban columns occupy most of the sprint board. The team uses these to track the progress of work during a sprint. See [Tracking Progress](#Tracking-Progress) for more details.

Each task is represented by a Post-it on the board. These Post-its move through the columns on the board throughout the sprint. At the end of a sprint, most (if not all) of the task Post-its will have migrated from the “To do” column through the “Doing” and “Verify” columns to the “Done” column.

#### Distractions

There is a reserved area on the sprint board for distractions. Development team members add a Post-it to this area whenever they deviate from sprint-related work. Team members add the duration of the distraction and their initials to the Post-it. The development team reviews distractions during the [retrospective](#Retrospective).

#### Retrospective Goals

There is an area on the sprint board for highlighting the current retrospective goals. These act as constant reminders to the team about what the agreed goals are for improving the process.

### Trello

## Guidelines

### Design

### Development

- [Source Control](docs/source-control.md) (needs updating)
- Teamcity
- Octopus
- Code Style
  - [JavaScript](docs/code-style/javascript.md)
  - [C#](docs/code-style/csharp.md)
