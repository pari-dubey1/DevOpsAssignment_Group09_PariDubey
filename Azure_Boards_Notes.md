# Azure Boards Notes – DevOps Assignment

## 1. Introduction

**Azure Boards** is a project management and work-tracking service provided by Microsoft as part of **Azure DevOps**. It helps development teams plan work, manage tasks, track bugs, organize sprints, and monitor project progress.

Azure Boards supports Agile methodologies such as **Scrum, Kanban, and Agile**.

## 2. Purpose of Using Azure Boards

Azure Boards can be used to:

- Create and manage work items
- Track bugs and issues
- Assign tasks to team members
- Set priorities
- Track task status
- Plan and manage sprints
- Create product backlogs
- Monitor project progress
- Track development activities
- Connect work items with code and Pull Requests

## 3. Important Azure Boards Concepts

### Organization
An organization is the top-level Azure DevOps environment where projects and related resources are managed.

### Project
A project contains all the work items, repositories, pipelines, boards, and other resources related to a software project.

### Work Item
A **work item** represents a unit of work in Azure Boards.

Common work item types include:

- **Epic** – A large business requirement or major feature
- **Feature** – A significant functionality within an Epic
- **User Story** – A requirement from the user's perspective
- **Task** – A specific piece of work
- **Bug** – A defect or problem that needs to be fixed

A common hierarchy is:

**Epic → Feature → User Story → Task**

### Backlog
The backlog contains planned work items that have not yet been completed.

### Sprint
A sprint is a fixed time period during which the development team works on selected backlog items.

### Assignee
The team member responsible for completing a work item.

### Priority
Priority indicates the importance of a work item.

## 4. Azure Boards Workflow

A basic workflow can be represented as:

**New → Active → Resolved → Closed**

Depending on the work item type and process template, the available states may differ.

### New
The work item has been created but work has not started.

### Active
The team is currently working on the work item.

### Resolved
The work has been completed from the development perspective and is ready for verification or closure.

### Closed
The work item has been completely finished and verified.

## 5. Creating a Work Item in Azure Boards

1. Open the Azure DevOps project.
2. Go to **Boards**.
3. Select **Work Items** or **Boards**.
4. Click **New Work Item**.
5. Select the appropriate work item type.
6. Enter the title.
7. Provide a detailed description.
8. Set the priority.
9. Assign the work item to a team member.
10. Add tags if required.
11. Set iteration/sprint information.
12. Save the work item.

## 6. Example Work Items

| Work Item Type | Title | Priority | State |
|---|---|---|---|
| Task | Create project repository | High | Closed |
| Task | Design project structure | High | Closed |
| User Story | Implement frontend | Medium | Active |
| Task | Configure deployment | High | New |
| Bug | Fix login validation | High | New |
| Task | Write project documentation | Medium | New |

## 7. Azure Boards Board

The Azure Boards Kanban board provides a visual representation of work items.

A basic board can contain:

### NEW
- Create repository
- Configure development environment
- Design UI

### ACTIVE
- Implement application features

### CLOSED
- Project setup
- Initial repository creation

The board allows team members to easily understand which tasks are pending, currently being worked on, or completed.

## 8. Azure Boards and GitHub Integration

Azure Boards can be integrated with GitHub to connect project management with source-code development.

A typical workflow is:

1. Create a work item in Azure Boards.
2. Note the work item ID.
3. Create a Git branch related to the work item.
4. Make code changes.
5. Commit the changes.
6. Push the branch to GitHub.
7. Create a Pull Request.
8. Review and merge the Pull Request.
9. Update the Azure Boards work item.

### Example

Suppose the Azure Boards work item ID is:

```text
#12
```

A corresponding branch could be:

```bash
git checkout -b feature/12-login
```

A commit could reference the work item:

```bash
git add .
git commit -m "Implement login feature #12"
git push origin feature/12-login
```

Referencing the work item helps connect development activities with the corresponding requirement or task.

## 9. Agile Methodology in Azure Boards

Azure Boards supports Agile project management.

In the **Scrum** approach, work is organized into sprints.

A typical workflow is:

**Product Backlog → Sprint Planning → Sprint → Daily Stand-up → Sprint Review → Retrospective**

### Product Backlog
Contains all planned features, user stories, tasks, and bugs.

### Sprint Planning
The team selects work items from the backlog for the upcoming sprint.

### Sprint
The team works on the selected work items.

### Daily Stand-up
Team members discuss their progress, current work, and any blockers.

### Sprint Review
The completed work is demonstrated and reviewed.

### Retrospective
The team discusses what went well, what problems occurred, and how the next sprint can be improved.

## 10. Benefits of Azure Boards

Azure Boards provides several benefits:

- Better task management
- Easy issue and bug tracking
- Improved team collaboration
- Visual Kanban boards
- Product backlog management
- Sprint planning
- Priority management
- Progress tracking
- Work-item traceability
- Integration with GitHub
- Integration with Azure DevOps services
- Better visibility into project status

## 11. Azure Boards in DevOps

Azure Boards can be combined with GitHub and CI/CD tools to create an end-to-end DevOps workflow.

A simplified workflow is:

**Azure Boards Work Item → Git Branch → Code → Commit → GitHub → Pull Request → CI/CD → Deployment → Work Item Update**

This provides traceability between requirements, development, source code, testing, and deployment.

## 12. Jira vs Azure Boards

| Feature | Jira | Azure Boards |
|---|---|---|
| Company | Atlassian | Microsoft |
| Main Purpose | Project & issue tracking | Work tracking & project management |
| Agile Support | Scrum, Kanban | Scrum, Kanban, Agile |
| Task Unit | Issue | Work Item |
| Backlog | Yes | Yes |
| Sprint | Yes | Yes |
| Kanban Board | Yes | Yes |
| Bug Tracking | Yes | Yes |
| GitHub Integration | Yes | Yes |
| CI/CD Integration | Yes | Strong integration with Azure Pipelines |
| Ecosystem | Atlassian ecosystem | Azure DevOps ecosystem |

## 13. Conclusion

**Azure Boards** is an effective work-management tool for software development teams. It helps teams organize requirements, create tasks, track bugs, manage backlogs, plan sprints, and monitor project progress.

When Azure Boards is integrated with **GitHub and CI/CD tools**, it provides end-to-end visibility and traceability throughout the software development lifecycle.
