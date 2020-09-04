# Project 3 Pitch

## Fork & Clone this repo.

Review the [Project 3 requirements](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/project-3#project-feedback-evaluation) and check out some [examples](https://tmdarneille.gitbook.io/sei-ga-sea/11-projects/past-projects/project3).

Provide information in the following sections:

----------------------------------------------------------
### Project Overview
##### (Include project idea/concept, project name, who owns git master repo on github, team name [if desired], team member roles, elevator pitch)

- Project Name: exitcodeZERO
- Git Master Repo: @imjchiang
- Team Name: reactiveMangos
- Roles: Each individual is in charge of the listed items (all team members will collaborate on those items)
    - Josh: models/schemas, auth, git master
    - Alice: routes
    - Irene: react components
    - All: styling

- Pitch: Alternative to stack overflow

----------------------------------------------------------
### Models and Schemas

Post:
- title: string
- tags: array
- format: array
- descriptions: array
- codeSnippets: array
- image (optional): array
- author: (userId)
- date(optional): date
- comments: array(CommentId)

Comment:
- comment: string
- format: array
- descriptions: array
- codeSnippets: array
- image (optional): array
- author: (userId)
- date(optional): date

User:
- username: string
- email: string
- password: string
- posts: array(postId)
- comments: array(commentId)
- date(optional): date

----------------------------------------------------------
### User Stories

##### Users are able to login and post issues they are having with their code

- Title: purpose of the code / error or issue they are having 
- Solved Tag: Indicates next to title whether the issue has been solved or not 
    - Clicking on this tag links to the solution the author of the question used
- Tags: tags help label and categorize the issue
- Description: describe the issue, things attempted, tried solutions, where you think potential issues are, constraints
- Code Snippets: Have option to enter in code snippets
    - can presss button to add additional snippets (ex: troubleshooting for multiple files)
- Image (optional): can post image of debugging screen, code, desired product, etc...

----------------------------------------------------------
### Wireframes

![Home Page](Home.png)
![Feed Page](Feed.png)
![Post Page](Post.png)
![CreatePost-EditPost Page](CreatePost-EditPost.png)
![Profile Page](Profile.png)

----------------------------------------------------------
### Additional Technologies
##### (MERN Stack expected [MongoDB, Express, React, Node], include any external APIs)

None

----------------------------------------------------------
### Work Allocation
##### Who is your Gitmaster? Who will be doing what? 
Each individual is in charge of the listed items (all team members will collaborate on those items)
- Josh: models/schemas, auth, git master
- Alice: routes
- Irene: react components
- All: styling

----------------------------------------------------------
### Daily Sprints
##### (or otherwise general plan for accomplishing tasks, preferably broken down by day)

Friday: 
- Set up master repo
Saturday: 
- master repo set
- models and schemas complete
- set up basic routes
- set up basic components
Sunday:
- complete "Post" routes
- complete "Post" and "Comment" components and subcomponents
- implement more auth stuff for "Post" and "Comment" routes and components
Monday:
- complete "CreatePost / EditPost" routes
- complete "CreatePost / EditPost" component and subcomponents
- implement more auth stuff for "CreatePost / EditPost" routes and components
Tuesday:
- complete "Feed" routes
- complete "Feed" component and subcomponents
- implement more auth stuff for "Feed" routes and components
Wednesday:
- complete "Profile" routes
- complete "Profile" component and subcomponents
- implement more auth stuff for "Profile" routes and components
Thursday:
- complete "Home" route
- complete "Home" component and subcomponents
- MVP reached
- add styling

----------------------------------------------------------

## Make a PR when you're done!
