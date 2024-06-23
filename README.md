[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15316182&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a browser-based application for maintaining code base and other types of software projects. Most commonly, it uses Git — the distributed version control system, which is primarily responsible for managing and versioning the code as well as other projects. One of the key benefits of using GitHub is its availability of tools and specific elements that can support development, combining resources for collaboration, and effectively managing projects. Here’s a detailed overview of its primary functions and features:Here’s a detailed overview of its primary functions and features:

Primary Functions and Features
1. Collaboration Tools
Pull Requests (PRs): Proposals to merge changes from one branch into another. They allow team members to review, discuss, and approve code changes before integrating them into the main project.
Code Reviews: Integrated tools for commenting on and reviewing code changes, which are typically part of the pull request process.
2.  Version Control with Git
Repositories (Repos): Central storage locations where project files and their history are stored. Developers create, manage, and share repositories for their projects.
Branches: Multiple versions of a repository that allow for the development of features or experiments in parallel without affecting the main project.


Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

GitHub is a web-based hosting service that uses Git, which is distributed version-control system. A GitHub repository or repo is a collection of files, updated and stored by Git.
As the term suggests, a GitHub repository – also referred to as a git repo usually – is a collection of files for a particular project that is centralised and governed online. It refers to the source code, documents, and any other files that you may need to roll back the program to. Structurally, repositories can be open (any member of the public can access it and contribute to it) or closed (access is only allowed after receiving permission from site administrators).

Most repositories are implemented using Git to maintain versions, to allow coordination of versions among developers. They also operate with GitHub’s web GUI and offer more possibilities of collaboration in addition to project management tools, which include pull requests, issues, and wikis.

Creating new repositories on GitHub can be a daunting task for most learners especially for those who have noPrevious experience with GitHub or any form of version control. That is why; in this tutorial, we will be learning how to create new GitHub repositories.
To create a new GitHub repository, follow these steps:To create a new GitHub repository, follow these steps:

Sign in to GitHub:

Click link of GitHub and enter to the site, then enter your account authorizations. And if you are one of those who do not have an account, then all you would be supposed to do is to open one.
Navigate to the New Repository Page:Navigate to the New Repository Page:

Go to the GitHub website and log in, then put your cursor in the search bar at the top of the website and click the button with the plus sign in the top right hand corner and choose “New Repository”.
Fill in Repository Details:

Repository Name: Click on “New repository” and type in the name that you want that repository to have. In fact, the domain must be unique within your account.
Description (Optional): Briefly describe your project and the main objectives, goals and actors involved.
Visibility: Select Public if the repository should be available for anyone to view; select Private if only you and other members of the collaboration should be able to view the repo.
Initialize the Repository:

You have the option to:You have the option to:
Add a README file: This includes a list of abbreviations and acronyms used in the document, a notice and a brief introduction to the repository.
Add . gitignore: A file advising Git which files should not be tracked in the directory.
Choose a License: Choose a license to set the rights people can claim to use your code.
Create Repository:

If you need more settings you can use the ‘Create repository’ button to complete the configuration.
The Stove ingredient is based on elements that one identifies when constructing a GitHub Repository.
Once your repository is created, here are the essential elements to include:Once your repository is created, here are the essential elements to include:

README. md:

This file can be seen as presenting an outline of the project: It should include:
Project title and description: What your project does Nature of your project is a basic name that reflects the function of your project.
Installation instructions: As mentioned earlier, this is a research project and the following steps will be followed to complete the project:

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Version Control is a system where a file or set of files are stored and every change that made to them is saved and labelled so that a given version can be brought back easily in the future. It facilitates a project by a number of people, retains records of the changes made, and one can return to previous versions.

Key Concepts in Git
Git is a distributed version control system that can meet growing needs for managing source code effectively.

Repository (Repo): A place in which the documents belonging to your project, as well as all versions of them, are to be kept. It can be local which resides on the local system or on the local machine where you are working or it can also be remote which resides on another server of the same network.

Commit: A list which should contain information about alterations to the repository. Every commit can be identified by a unique identifier (hash) and there is a message attached to it which contains information concerning the changes.

Branch: It begins with another form of organization, a distinct line of development. Branches are where you can actually do a new feature or a fix separately from the actual project (This is often done on the actual or main/base branch). It is possible to merge branches when the feature is implemented, as a result of which there will be a need to merge branches.

Merge: The propagation of changes across various branches in a particular version. Git merges automatically, and it is possible to encounter issues in the updated version of the code where the same part has been amended by different branches.

Pull: Pulls updates from another repository & incorporates the changes into your current repository.

Push: Pushes local changes to a remotes repository updating such a repository with all the commits that you made locally.

Clone: Develops a local copy on the computer of a repository that exists elsewhere on the internet or of a specific branch.

Fork: Subversion repository with personal copy on GitHub of some other person. Forking is also important in cases where you try out various changes without having an impact on the initial work done.

Pull Request (PR): Here, people can present notions regarding changes in a particular repository. When you fork a repository, you can make modifications and commit messages to them and then make a pull request to the original repository.


Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

Branch is similar to a branch of a tree; It is a copy of a repository which may or may not have a committed upstream. These enable developers to make changes to a feature, a fix, or an experiment independently of the main branch that is also termed as the master branch. This segregation allows one to avoid deploying unstable code to the production version of the said project. 
 
 Importance of Branches 
 Isolation: This way, different branches of the project may have different changes at the same time, which retains its distinctness from the original branch. 
 Collaboration: Code can be managed such that many developers are able to work in different branches of the particular code. 
 Version Control: Branches give the possibility to track modifications and to carry out various versions of a project. 
 Creation of a branch and change management and merger of a branch 
 Creating a Branch: 
 
 In the GitHub web interface:In the GitHub web interface: 
 Go to your repository. 
 Next to the branch name right now it is main, click on the dropdown list. 
 Add a new branch and click on the create button. 
 Using Git command line: 
 sh 
 Copy code 
 git checkout -b feature-branch 
 Making Changes: 
 
 Check out your new branch:Check out your new branch: 
 sh 
 Copy code 
 git checkout feature-branch 
 Edit your changes on the site using your code editor. 
 Stage and commit your changes:Stage and commit your changes: 
 sh 
 Copy code 
 git add . 
 git commit -m “description of changes that has been done” 
 Pushing Changes to GitHub: 
 
 Push your branch to GitHub:Push your branch to GitHub: 
 sh 
 Copy code 
 git push origin feature-branch 
 Merging Branch Back into main:Merging Branch Back into main: 
 
 Create a Pull Request (PR) in GitHub:Create a Pull Request (PR) in GitHub: 
 Go to your repository. 
 Go to the “Pull requests” tab. 
 Click "New pull request". 
 Feature branch should be selected on the right side of the Pull Request as a compare branch whereas main has to be selected on the left side of Pull Request as the base branch. 
 Click , Create pull request and submit.
Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

### What is a Pull Request in GitHub? 
 
 In GitHub, a **pull request** (PR) is a procedure through which an individual submits a set of changes to a repository for review and possible inclusion in the project’s main version. It is useful, although not critical, for pair programming, reviewing the code commitments, and keeping the code clean in a team project. 
 
 ### How Pull Requests Facilitate Code Reviews and Collaboration 
 
 1. **Code Review:** Facilitates for the team members to discuss about the changes that have been made to the code before these are integrated. 
 2. **Discussion:** Facilitates communication concerning certain lines of code and in general concerning the changes to be made. 
 3. **Approval Workflow:** Enables project maintainers to confirm a change or to request a change. 
 4. **Continuous Integration:** Involves the automation of testing as well as other processes for change validation. 
 5. **Change Tracking:** Records the variations of it and also the discussions that have took place concerning the feature or the bug fix. 
 
 ### Steps to Create a Pull Request 
 
 1. **Create a Branch:** Create a new branch off the master branch Using: 
 ```bash 
 git checkout -b feature-branch 
 ``` 
 2. **Make Changes:** Use: git commit -m “Message” for main changes to the new branch. 
 ```bash 
 git add . 
 It is in form of source code, and one commands another one to check the changes and then commit at the repository using the command git commit -m “Description of changes”. 
 ``` 
 3. **Push Branch:** Commit the branch to GitHub: 
 ```bash 
 git push origin feature-branch 
 ``` 
 4. **Open Pull Request:** Go to the GitHub repository and open the directory folding on the left side then click on the **”Compare & pull request”** button. 
 5. **Fill Details:** Add title, description of the annotation and inform the system if there is a need to assign reviewers. 
 6. **Create Pull Request:** Go to the newly created branch, click **”Create pull request”**. 
 
 ### Steps to Review a Pull Request 
 
 1. **Open the PR:**Navigate to the repository in the browser and go to its **Pull Requests** section to choose the desired PR. 
 2. **Review Changes:** Use the diff to view codes, to view changes made to the code and the whole files changed. 
 3. **Add Comments:** Give your comments on any lines or the entire PR if you wish to. 
 4. **Approve or Request Changes:** 
 - If satisfied, click **”Approve”**. 
 - To request changes click on **”request changes”** and give feedback if there are changes to be made. 
 5. **Merge PR:** After it, integrate the PR into the main branch: usually, the **”Merge pull request”** button is used for this action. 
 

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
GitHub Actions are scripts or processes that are built right into your GitHub repository and trigger specified actions. CI/CD tools help you to send scripted build and testing pipelines and deployment so that you can build per change. 
 
 Example of a Simple CI/CD Pipeline using GitHub Actions:Example of a Simple CI/CD Pipeline using GitHub Actions: 
 Trigger: Launch an action on the GitHub that will run each time the main branch is receiving a push. 
 
 Build: Perform an action for your project. For instance, if using Node-js, instead of searching for ‘node js interview questions’ in Google, you can type directly ‘interview questions about node js into google’. js, you might use an action that installs dependencies and the tests the application (npm install and npm test). 
 
 Test: Introduce a step to run tests. This makes sure that your code has gone through all the defined tests in place to make sure that it is work able. 
 
 Deploy: If tests are ok, then launch your application. For instance, you might have targets to deploy to a staging environment on the AWS or another cloud. 
 
 Notify: If desired, inform changes (e. g. , in Slack or via email) about the pipeline. 
 
 Here’s a simplified YAML configuration (/. github/workflows/ci-cd. yml) for such a pipeline:Here’s a simplified YAML configuration (/. github/workflows/ci-cd. yml) for such a pipeline: 
 
 yaml 
 Copy code 
 name: CI/CD Pipeline 
 
 on: 
 push: 
 branches: 
 - main 
 
 jobs: 
 build: 
 runs-on: ubuntu-latest 
 
 steps: 
 - uses: actions/checkout@v2 
 
 - name: Install dependencies 
 run: npm install 
 
 - name: Run tests 
 run: npm test 
 
 - name: Move to staging 
 ># Specific action that is taken to deploy resources or the script that is run to deploy the resources 
 run: | 
 Using the operating system command, echo, the following message can be sent to the staging environment; Deploying to staging environment. . . 
 # Your deployment script or command here 
 
 - name: Notify deployment 
 ># action or script to be sent as a notification 
 run: This call will display the following script after it has successfully deployed to the staging environment: echo “Deployment to staging completed successfully!” 
 In this example: 
 The workflow operates on every push that targets the main branch. 
 It runs code review, sets up the dependencies, executes various tests, deploys to a staging environment as it is replicated here, and informs about the state of the deployment.
Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Microsoft Corporation originally created Visual Studio, which is an IDE that is widely used by developers. Some of the enhanced features consistent of editing code, debugging tools for projects, and most importantly has support for many different languages.

Visual Studio Code (VS Code), on the other hand, is a comparatively new lightweight, cross-platform, open-source integrated development environment from Microsoft. Community is open and supports many programming language and extensions which makes it highly customizable. In contrast to Visual Studio, VS Code is less weighty, launches much faster, and is more suitable for code editing as well as automating various tasks in the process of software development rather than having as many built-in opportunities for integrated developing and debugging as Visual Studio.
Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
To integrate a GitHub repository with Visual Studio:To integrate a GitHub repository with Visual Studio: 
 
 1. **Clone Repository**: Add the required project type and open Visual Studio and then you can clone the above repository using Git menu or Team explorer. 
 
 2. **Commit and Sync**: Local edit code, local commit, and then send it to the GitHub to push the changes in the repository. 
 
 3. **Branching and Pull Requests**: It is also possible to manage branches, perform the creation of pull requests and merging of changes right from Visual Studio. 
 
 **Enhancement of Development Workflow**: 
 - **Seamless Collaboration**: Eliminates concerns of version control by using Git for the team members to work together effortlessly. 
 - **Integrated Toolset**: Real time collaboration that gives direct access to Git commands and pull requests as well as branches within the IDE. 
 - **Version Control**: Manages changes, code reviews and version history within the development environment should be effectively managed.
Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Visual Studio provides several powerful debugging tools:Visual Studio provides several powerful debugging tools: 
 
 1. **Breakpoints:** This would allow at Developers to stop the program at a given line of code in order to have a look at the state of a variable or the value of an expression. 
 
 2. **Watch Windows:** Enables one to trace the values of the variables and expressions as the code is being processed so that the wrong values can be noted. 
 
 3. **Immediate Window:** Allows running particular code at the time of debugging, used to test fragments and calculate expressions. 
 
 4. **Call Stack:** Demonstrates how the functions have been called to achieve the current program execution placement and helps to identify program flow. 
 
 5. **Debugging Toolbar:** Has features to follow through the code at single line (step into, step over, step out) to debug and find bugs. 
 
 With these tools, developers can systematically analyze and correct the programs by recognizing that values have been input incorrectly, comprehend the use of flow control structures and, in general, try out hypotheses regarding the behavior of a code segment.
Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
Everything in the GitHub links to Visual Studio, and version control, issue tracking, and code review are part of the IDE. Another way that developers are able to take advantage of working with Visual Studio is through cloning repositories, branches creation, changes making and commits right from Visual Studio are in synchronized with GitHub. In this integration, it also increases the team effectiveness in deliverables and improves the overall quality of code. 
 
 **Example:** Some software developers that are in a team developing a web application use GitHub for version control and managing issues. For coding, reviewing, and Pull requests they use Visual Studio, whereas for tracking the tasks they use visual studio. These integrations let them have a single code base that can be easily managed, tracked, and collaborated at any point in the development process.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
