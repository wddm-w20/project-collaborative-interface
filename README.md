# Course Project: Collaborative Application

## Overview

Using your knowledge of application design and development, create an application to facilitate collaboration between two or more remote users. The theme or topics is of your choosing, but consider collaboration may happen anywhere, including work, play, family and friends.

## Goals

1. Demonstrate application structure and functionality
2. Enforce collaborative workflow for students/developers
3. Apply UI/UX skills using a common/ubiquitous framework/library

## Deliverables

### Part 1: Getting started

#### Planning & Discussion
1. Form a team of 3 or 4 students to collaborate on project ideas
2. Individually, each member should think of three unique (existing) collaborative applications, not including obvious choices, like Slack, Zoom, Facebook, etc. Be creative and think *outside the box*
3. As a group, take turns discussing your findings and analyze the merits of each
4. Select the most interesting idea as a group and discuss what you believe the structure of the application looks like. Be sure to consider:
   1. Consider what type of data might be required to store
   2. What type of underlying technology is required to "collaborate", describe it
   3. How is the routing of the application handled


#### Application
2. Create a Github Organization for your team
3. Create a repo named after your organization in this format: `[orgname].github.io` (where `[orgname]` is replaced by your organization name)
4. Give access to the entire Organization (or just the Repo) to your team members
5. Create a `README.md` file in the root, with the following in it, then commit to `master`:
	```
	# Community Application

	## Group
	```
1. Each member should write a ticket reminding themselves to "Add my name and work to the README.md"
   1. Assign it to yourself
   2. Add at least one "label" to the issue (use the most appropriate one)
1. Each member should now clone the repo, create a unique branch, and in that branch, add their name to a list directly under the `# Group` heading
2. Each member will link the name from the list to a section below, subtitled with their name, for example `## Tim Berners-Lee`
3. Under their named section, each user will include notes on their ideas and contributions from the group planning/discussion 
4. When you commit your work, use the commit message to `close #` the ticket
5. Each member should create a pull request
6. As a group, select one person to merge all of the requests into `master`
7. After managing all merge conflicts, commit all the changes to `master` and push the branch to remote
8. Prune all of the name branches to demonstrate that functionality
9. On Slack, create a group message that includes all members of your group and the instructor, then paste the link to your Github Organization into it 
   - You will use this repository for the remainder of the term
   - Commits to `master` must be done *at least* **each Friday by 6pm** for the remainder of the term

### Part 2: Application prototype

Coming soon.

### Part 3: React application

Coming soon.

## Project requirements

- Delegate roles to all group members
- Decide on any dependencies your team may wish to incorporate (ie, Sass, etc)
- Develop a plan for the layout of each page
- Decide on the general design system (colours, fonts, etc)
- All work must be done in branches
- All code communication must go through "Issues", including (but not limited to):
  - Code bugs
  - Design decisions
  - Assigned tasks
  - Content changes
- Issues must be managed (open/comment/close)
  - It might be wise to assign one user the role of "project manager"
- Include a folder of any documentation that was completed during this project (links, PDFs, compressed images, etc - no large "original" files, please!)


## Git management criteria

- Ensure each feature or bug fix has its own branch during development _(don't use named user branches for all of your work!)_
- There should not be a `node_modules` folders in any of your branches
- Use `Issues` to track everything! Even if they're just upcoming features or proposals (use _labels_ to track their status/significance)
- All users should contribute to the Issues and documentation. 
  - At the end of the project, be sure to add a paragraph of text in the `README.md` file to explain your project and repository management strategy (how work was delegated, how pull requests and merges were handled, etc)
