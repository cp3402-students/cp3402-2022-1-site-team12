[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

Workflow and how to integrate
===

Our team got together and brainstormed how we would like the redesigned website to look. We produced a template and pinned it to our Discord channel; for us to be able to refer to. Our template included ideas such as what colours to use on the website, what content we should keep and where it should go, how many tabs to use, and so on. This was also pinned to our discord channel.
When we start a task, we create a card and add it to our Trello Board. The person working on the task can then move the card to the ‘In Progress’ section. When the task is finished, the card can then be moved to the ‘Done’ section. This allows everyone to see ‘at a glance’ who is working on what, and whether what they are working on is ‘In Progress’ or ‘Done’.
Making changes to the website theme are done locally whilst making changes to the sites content is done in the online WordPress editor. Theme changes made locally are done in PHPStorm, then uploaded to our GitHub repository using Git, while changes made online are made directly on the site in ‘edit mode’ and later ‘published’, when everyone is satisfied with the changes. When you first take over the site, all you need to do is have PHPStorm installed onto your machine, add Git as version control and then it is a simple procedure to clone the repository. Before beginning to work locally, we check for changes by opening the terminal and entering git status. We can then ‘pull’ the changes onto our machines, work on our appointed task, then ‘push’ our changes onto the GitHub repository.

### Tools Used
* `Trello` – Workflow Management
* `Discord` – Communication
* `WordPress` – CMS
* `Git` – Version Control
* `PHP Storm` – IDE
* `Docker and Vagrant` – Local Environments

### Workflow Management (Trello)
To help manage project workflow the team has adopted `Trello`; Trello is an `easy to use` to `workflow management board` that allows the team to get `at-a-glance` information on assigned tasks. `New members` simply must `check the board` to see what tasks they have been assigned and complete them accordingly. `Experienced members` can `check the board`, `add cards` and `assign members` to said cards.

### Communication (Discord)
`Discord` was chosen for the `team’s communication` as all members of the team had previously used Discord and had found it `easy to use`, `upload files`, `share their screen`, `hold meetings`, and work with team members whilst being in `different locations`. So, we decided to put a `Discord link on Slack`, thus allowing anyone using Slack to be able to access our Discord channel. We have also integrated our Slack channel with Discord and GitHub.

### Version Control (GitHub)
`GitHub` is an industry standard `distributed version control` that is used within the Team12 `theme development`. GitHub is to be `integrated with PHPStorm` or a members preferred IDE; when opening a project members are to `check for new changes` by entering `git status` in the terminal and then `pulling the changes` if necessary. Once a member is done add a feature or style they are to `commit the change` with an appropriate commit note and then `push the changes`.

### IDE (PHPStorm)
`PHPStorm` is the `recommended IDE` for the `development of the theme`, it incorporates `easy integration with GitHub`, `easy to download plugins`, `easy to use GUI`, `auto code complete` and much more. It can `connect to Docker` and Vagrant although is issues are found there are working work arounds.

### Virtual Environments (Docker & Vagrant)
For windows users it is recommended to install and use `Docker` for their `virtual environment`, Docker provides a `free`, `hassle less setup` that allows users to create a virtual environment `easily and speedily`. For `Linux users` it is recommended to use `Vagrant with VirtualBox`; this method requires more setup however Linux users have reported issues trying to setup Docker.

### Local Environment & Automation Workaround
An issue the team faces with local development is creating automation between the theme and the local environment; to solve this problem the team has a workaround:
* Save the changes made towards the theme.
* Copy the theme file.
* Locate the theme file in the local environment folder on your machines
* Paste over the theme file with the new saved and copied theme file.
* Check the local environment of the site to see changes made. 