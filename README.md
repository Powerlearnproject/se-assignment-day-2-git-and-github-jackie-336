[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18435417&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
                 1. Fundamental Concepts of Version Control:
-Repository (Repo): This is the database where all your project files;including history, are stored. A repo contains all the changes made over time, allowing you to track revisions and the entire project’s history.
-Commit: A commit is like a snapshot of the project at a particular point in time. Each commit contains a record of what changes were made to the files and who made them. Each commit is identified by a unique hash.
-Branching: Branches allow developers to work on separate features or tasks without interfering with the main codebase . Once the work is completed, the branch can be merged back into the main project.
-Merging: When a developer finishes working on a branch, they "merge" it back into the main branch. This can sometimes cause conflicts if two different people modified the same part of the code, which then needs to be resolved manually.
Pull Requests : In platforms like GitHub, pull requests are used to propose changes from one branch  to another . Other team members can review the proposed changes before merging them into the main project.
                     2. Why GitHub is Popular for Version Control:
-Git-based: GitHub is built on top of Git, a distributed version control system . Git is highly efficient and allows developers to work offline, with each developer maintaining their own full copy of the project, which can later be synced with the central repository.
-Collaboration: GitHub makes collaboration easy by providing a user-friendly interface for reviewing, merging and discussing code changes. It also offers features like pull requests, issue tracking and project management boards to streamline teamwork. 
-Cloud-Based: GitHub hosts repositories in the cloud, meaning that developers can access their project from anywhere with an internet connection. This makes it easier for teams spread across different locations to collaborate.
-Integration & Automation: GitHub integrates with many tools that enhance the development process, including continuous integration/continuous deployment pipelines, code quality checks and automated testing tools.
-Open Source & Community: GitHub is widely used in the open-source community, where developers share code, contribute to other projects and leverage others' work. The platform’s vast community is one reason for its popularity.
                                 3. How Version Control Helps Maintain Project Integrity:
-Traceability: Version control ensures that every change is logged, providing a clear history of the project. This helps developers understand the evolution of the project and know exactly who made specific changes, which is vital for debugging and accountability.
-Backup & Recovery: Since every version of the code is stored in the repository, if something breaks or a mistake is made, it’s easy to roll back to a previous, stable version. This helps prevent major data loss.
-Collaboration Without Conflict: Multiple developers can work on the same project simultaneously. Version control allows them to work on separate branches and then merge their changes without affecting each other's work. GitHub also facilitates conflict resolution when different developers change the same part of the project.
-Consistency Across Environments: With version control, everyone on a team is working with the same codebase. This ensures that no one’s work diverges drastically from others, helping avoid "works on my machine" issues.
Audit Trails: In cases of debugging, tracking bugs, or investigating why a certain decision was made, version control provides a detailed audit trail of all code changes and rationale behind them .

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
1. Sign In to GitHub (or Create an Account)
2. Create a New Repository
3. Fill Out Repository Details
4.  Create the Repository
5.  Clone the Repository to Your Local Machine
6.   Add Files to the Repository
7.   Commit and Push Changes to GitHub
8.   Further Configuration

                                  Key Decisions During the Setup Process:
. Repository Visibility (Public or Private): Decide whether you want your project to be open-source or if it should remain private.
. License: Choose whether to apply an open-source license. It’s important to protect your code and clarify usage rights.
. README: Including a README.md is highly recommended as it gives users context about your project.
. gitignore: Choose an appropriate .gitignore template to ensure irrelevant or unnecessary files are not tracked.
. GitHub Actions: If you want to automate , GitHub Actions is a useful tool to set up right from the beginning.
## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
                         =Importance of the README File
(i) Project Introduction and Context:
-A README provides an overview of what the project is about, explaining its purpose, goals and functionality. This helps users quickly understand the value of the project and whether it suits their needs.
(ii) Instructions for Setup and Usage:
-The README typically includes step-by-step instructions on how to install, configure and run the project. This is essential for users and developers who are looking to get started with the code. Without clear instructions, users may become frustrated and abandon the project.
(iii) Collaboration and Contribution Guidelines:
-For collaborative projects, the README file often includes guidelines for how others can contribute, report issues, or submit bug fixes. It helps ensure that everyone is aligned with the project's objectives and that contributions follow a consistent process.
(vi) Documentation and Examples:
-The README often serves as the main source of documentation. Including code examples, use cases, or demonstrations within the README can help users better understand how to interact with the project.
(v) Professionalism and Organization:
-A well-organized and clear README shows that the project is well-maintained and thought-out. It sets a professional tone and gives users confidence in using the code and collaborating.

                          What to Include in a Well-Written README;
          1. Project Title and Description
          2. Badges 
          3. Table of Contents 
          4. Installation Instructions
          5. Usage Instructions
          6. Screenshots
          7. Contributing Guidelines
          8. Licensing Information
          9. Acknowledgments 
          
                                =How the README Contributes to Effective Collaboration
(I) Onboarding New Contributors: A comprehensive README provides new developers with everything they need to get started, reducing the time they spend figuring out the project setup or understanding the project’s goals.
(II) Clear Contribution Process: By outlining how to contribute, what standards the code should meet and how to submit changes, the README ensures that contributions are structured and easy to review. This makes it easier for maintainers to evaluate pull requests and integrate changes effectively. 
(III)  Consistency in Development: Clear instructions on setup, dependencies and usage help ensure that everyone is on the same page and avoids inconsistencies in development environments, which can be frustrating for collaborators.
(IV)Effective Communication: The README acts as the first point of communication with potential users and contributors. It communicates the project’s vision, instructions and necessary information in an organized manner.
(V)Documentation for Users: If your project is a library, framework or tool, the README can provide essential documentation for users to understand how to use it effectively. This can reduce confusion and encourage adoption.    

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
1. Public Repository
= Advantages:
(1)Open Collaboration:
-Public repositories are ideal for open-source projects because anyone can view the code, submit issues, or contribute through pull requests (PRs). This opens the project to a wider pool of contributors, encouraging collaboration from a global community.
-New developers or contributors can learn from or improve upon the code, leading to innovation and faster progress.
(2)Community and Visibility:
-Since the repository is visible to everyone, it can attract a large number of users and developers. This visibility is especially valuable for building a community around a project, gaining traction and showcasing your work to potential employers or clients.
-Projects in public repositories are indexed by search engines, which increases the project's discoverability.
(3)Free Hosting:
-GitHub offers free hosting for public repositories, which is a major advantage for personal projects, small startups or open-source initiatives. This reduces the financial burden of hosting your project elsewhere.
(4)Issue Tracking & Feedback:
-Public repositories allow for easy issue tracking and discussions from a wide audience. Anyone can report bugs, suggest new features, or provide feedback.
                            Disadvantages:
  (i)Lack of Privacy:
-All files, code, and history are visible to the public, which may not be ideal for projects containing sensitive information, proprietary code or unfinished work.
-If the project is in an early stage or experimental, you might prefer to keep it private to avoid premature exposure.
(ii)Security Risks:
-Public repositories can be a target for malicious users who might try to exploit vulnerabilities in the code. You also run the risk of someone stealing your code or misusing it without proper attribution.
(iii)Contributing Control:
-While anyone can contribute to a public repository, this also means you may get many irrelevant or low-quality contributions. Maintaining the quality of contributions may require more oversight.
(v)Potential for Overwhelm:
-With large public repositories, there may be an influx of issues, pull requests or questions from a broad audience. This can be overwhelming if not properly managed or if the maintainers do not have the resources to handle the volume of activity.
                               2. Private Repository;
            =  Advantages:
   (1)Confidentiality:
-Private repositories allow you to keep your code and project details hidden from the public. This is especially important for proprietary code, internal projects, or when working on sensitive information that you don't want to share publicly.
(2)Control Over Access:
-You can control exactly who has access to the repository. This makes it easier to manage team members and collaborators, ensuring only the right people can view or contribute to the project.
-You can invite collaborators, set permissions  and even revoke access when needed. This level of control is useful for managing teams within an organization.
(3)Security:
-Since the repository is private, you minimize the risk of exposure to malicious users, hackers, or unauthorized individuals. This can provide peace of mind, especially when working on high-risk or high-value code.
(4)Early Stages or Sensitive Work:
-For projects in their early stages, when you’re experimenting or testing ideas, a private repository allows you to work without the pressure of public scrutiny.
-Private repositories can also be used for working on closed-source applications where you don't want to release the code to the public until the project is ready.
                               Disadvantages:
(I)Limited Collaboration:
-Since only invited collaborators have access, private repositories restrict who can contribute. While this allows for more controlled collaboration, it also limits the potential pool of contributors.
-If you want to expand the project or invite external contributors, you need to manage invitations and permissions carefully, which can be cumbersome if the team is large or changes frequently.
(II)Costs:
-GitHub’s free plan allows for private repositories, but with limitations . For larger teams or organizations with many private repositories, you might need to pay for GitHub's premium plans, which can increase costs.
(III)No External Feedback:
Unlike public repositories, you won't receive unsolicited feedback or bug reports from users who may be interacting with your project. This could slow down the identification of issues or areas for improvement, as contributions are restricted to a smaller group.
(IV)Visibility:
-A private repository does not benefit from public visibility. It won’t be indexed by search engines and you won’t gain exposure to the broader community or potential users and collaborators unless you decide to make it public at a later stage.
                                 Key Considerations for Collaborative Projects;
             =Public Repositories:
-Best suited for open-source projects where the goal is to engage with a wide range of contributors and build a community around the project.
-Ideal for public documentation, shared knowledge, and rapid iteration, as anyone can contribute, file issues and suggest improvements.
-Public repositories benefit from feedback and bug reports from users worldwide, allowing for faster identification of problems and potential solutions.
               =Private Repositories
-More suitable for private teams working on internal projects, proprietary code or commercial applications that need to remain confidential until they’re ready for public release.
-Great for companies or organizations who want to control access to their codebase and work with specific collaborators or clients.
-Useful during the early development phase, when a project is being refined and you don’t want to expose unfinished or experimental work.


## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
                                      =Steps to Make Your First Commit to a GitHub Repository
       1. Create a GitHub Repository
Before you can make a commit, you need a repository on GitHub. Here are the steps to create one:
.Log in to GitHub: Go to GitHub.com and log in or create an account.
.Create a new repository: Click on the "+" icon in the top right corner of the screen and select New repository.
.Fill in repository details: Choose a repository name, descriptioN and whether it should be public or private.
.Initialize the repository: Optionally, you can initialize the repository with a README file . This file can contain basic information about your project.
        2. Install Git Locally
You need Git installed on your computer to interact with GitHub and make commits. Here's how:
.Install Git: Download and install Git from git-scm.com.
.Configure Git: After installation, configure your Git username and email. Open a terminal (or Git Bash on Windows) and run the following commands:
bash ,COPY
        3. Clone the GitHub Repository Locally
-Now that you have a repository on GitHub, you need to clone it to your local machine to start making changes. You can clone the repository using the following steps:
.On the GitHub repository page, click the green "Code" button and copy the repository URL (either HTTPS or SSH).
.In your terminal, navigate to the directory where you want to clone the repository and run
          4. Make Changes to Your Project
-Once you’ve cloned the repository, navigate to the local repository folder on your machine. Now you can start making changes:
Create a new file or modify existing files.
            5. Stage the Changes     
  -Before you can commit, you need to stage the changes, which means preparing them to be committed. To do this, use the git add command:
.Stage a specific file
.Stage all modified files
                   6. Commit the Changes
-Once the changes are staged, you’re ready to commit them. A commit includes a commit message that describes what was changed:
.To make the commit, run
                        7. Push the Commit to GitHub
-Now that you’ve made your first commit locally, you need to push it to the remote repository on GitHub. This uploads the commit to GitHub and makes it visible in your online repository.
                                  8. Verify the Commit on GitHub
-After pushing, go to your repository page on GitHub, and you should see your commit in the repository’s history. The commit message will be displayed, and you can also see the exact changes that were made.

                                =How Commits Help in Tracking Changes and Managing Versions
1. History of Changes
Commits provide a complete history of changes made to your project. Each commit has a unique identifier (hash), and you can view the changes made at each 
      step. This allows you to track the evolution of your project over time.
.View commit history: You can view the commit history in GitHub or using Git commands
Run the following command to push your changes
How Commits Help in Tracking Changes and Managing Versions
2. Revert to Previous Versions
3.  Compare Changes
4.  Collaboration
5.  Branching and Version Control
## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
=Branching in Git is a powerful feature that allows you to diverge from the main line of development to work on different tasks, features or bug fixes in isolation. Instead of making changes directly to the main branch , you create a branch to work on a separate version of your project. Branching allows you to experiment, make updates and refine code without affecting the main codebase.
                                        =Why Branching is Important for Collaborative Development on GitHub;
Branching is a vital feature for collaborative development because it:
.Isolates Work: It allows multiple developers to work on different parts of the project at the same time without interfering with each other's work.
.Prevents Conflicts: By working in separate branches, developers can independently make changes and then merge them later. 
.Facilitates Parallel Development: Teams can work on multiple features, bug fixes or experiments simultaneously by creating different branches for each task.
.Ensures Stability: Developers can continue pushing changes to feature branches without affecting the stability of the main branch, which may be running production code.
.Code Review: Branches enable pull requests, which allow team members to review and discuss code before it gets merged into the main branch. This ensures better quality control and collaboration.
                   The Process of Creating, Using, and Merging Branches in a Typical Workflow
1. Creating a Branch
. To create a new branch, use the git branch command:
.To both create and switch to the new branch in one step, you can use:
(Alternatively, if you’re using Git 2.23 or higher, you can use the git switch command:)
2. Working on Your Branch
. Edit files.
.Stage changes.
.Commit changes:
3. Pushing Your Branch to GitHub
. First, push your branch to GitHub:
:If it’s your first time pushing this branch, Git will automatically set up the remote tracking for this branch. After that, you can simply use git push for subsequent pushes.
4. Creating a Pull Request (PR) on GitHub
-Once your work in the branch is complete, you’ll want to merge it into the main branch. The typical way to do this is by creating a Pull Request (PR) on GitHub.
5. Reviewing and Merging the Pull Request
6.  Deleting the Branch
                              Typical Git Workflow for Collaboration Using Branches;
   (1) Create a branch:
  (2) Push your branch: 
(3)Open a pull request:
(4)Review and merge:
(5)Delete the branch:
                                        =Benefits of Using Branches in Collaborative Development
-Isolation: Branches isolate features, bug fixes, or experiments, ensuring that changes don’t affect the main branch until they’re ready.
-Parallel development: Multiple team members can work on different tasks simultaneously without blocking each other.
-Better organization: Git allows for organized, manageable codebases, where each feature or task has its own branch.
-Easier collaboration: Branches allow for code reviews, discussions, and easier tracking of individual contributions.
## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
     =A Pull Request (PR) is a core feature of GitHub and a critical element of the collaborative workflow in software development. Pull requests allow contributors to propose changes to a project, which can then be reviewed, discussed and merged into the main codebase. This process provides a structured way for team members to collaborate, review code and ensure the integrity and quality of the project before changes are incorporated.
                                       =How Pull Requests Facilitate Code Review and Collaboration
(I)Code Review: PRs enable team members to review the proposed changes before they are merged. Code review is a crucial part of maintaining code quality, ensuring that bugs are caught early, and improving the overall reliability of the project. PRs provide a clear view of the differences between the feature branch and the main branch, making it easy to compare code and check for issues.
(II)Discussion and Feedback: Pull requests allow team members to comment on the changes, ask questions and provide feedback. Discussions can be held directly within the PR, making it easy for everyone involved to track and respond to feedback in one place. This ensures that everyone is aligned on the changes before they are incorporated into the main branch.
(III)Visibility and Transparency: Since PRs are public (within the repository), every team member can see the proposed changes, how the code evolves, and who is contributing what. This transparency helps to avoid conflicts, encourages collaboration, and provides a record of decisions made during the development process.
(IV)Quality Control: By using PRs to review changes, you can enforce best practices, ensure code standards are met, and ensure that tests (if applicable) are passed. This process helps catch errors early, improves the quality of the codebase, and maintains consistency across the project.
(V)Testing Before Merging: GitHub allows you to integrate automated testing, such as running unit tests or continuous integration (CI) checks, within a PR. Before merging the changes into the main branch, you can verify that everything works as expected by running tests and CI checks
(VI)Collaboration and Documentation: Pull requests act as a collaborative document, allowing developers to explain the rationale behind the changes they’ve made. They can describe why certain decisions were made or how a problem was solved. This helps everyone on the team understand the reasoning behind the changes, making future collaboration more effective.
                                         =Typical Steps Involved in Creating and Merging a Pull Request
Step 1: Create a Feature Branch
Step 2: Make Changes and Commit
Step 3: Push Your Branch to GitHub
Step 4: Create a Pull Request 
Step 5: Review and Discussion
Step 6: Address Feedback
Step 7: Merge the Pull Request
Step 8: Delete the Feature Branch
                                 Benefits of Pull Requests in the GitHub Workflow
-Structured Code Review: Pull requests provide a formalized process for reviewing and discussing code before it is merged into the main branch. This ensures that code quality is maintained and that the changes are carefully considered.
-Ensures Quality and Consistency: Pull requests help catch issues early and encourage developers to follow best practices. Automated checks, such as continuous integration (CI), can be integrated to ensure that tests pass before merging.
-Collaborative Discussion: PRs provide a central place for team members to discuss proposed changes. This collaboration helps developers align on solutions and improves communication within the team.
-Audit Trail: Pull requests serve as a historical record of changes. They capture not only the changes made but also the discussions and decisions that led to those changes, which is valuable for future reference.
-Safe Integration: By reviewing and testing changes in a separate branch, pull requests minimize the risk of breaking the main codebase. Changes can be tested and refined before they affect the live project.

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
               Concept of Forking a Repository on GitHub
Forking a repository on GitHub is the process of creating a personal copy of someone else's repository under your GitHub account. This allows you to experiment with the project, make changes and propose modifications, all while keeping the original project intact. When you fork a repository, you are essentially creating an independent copy of the codebase that you can freely modify without affecting the original project unless you decide to contribute back.
                   How Forking Differs from Cloning
                  . Purpose: Forking is used when you want to contribute to someone else's project or take a copy of their project and make independent changes. It is typically used in an open-source collaboration model.
.Where it happens: Forking happens on GitHub itself. It creates a new repository under your GitHub account, which is a copy of the original repository.
.Contribution: Forking is generally used when you want to contribute to a project, usually by creating a Pull Request (PR) from your forked repository to the original repository.
.Workflow: You can push changes to your forked repository and then create a PR to propose those changes to the original repository.
                           2. Cloning
-Purpose: Cloning is used to create a local copy of a repository on your machine so you can work on it offline.
-Where it happens: Cloning happens on your local machine. It creates a copy of the repository, including all files, branches, and history, on your local filesystem.
-Contribution: You can clone any repository , make changes, commit them locally, and then push them to a remote repository .
-Workflow: After cloning, you can work locally, create branches, and commit changes. If you want to contribute to an upstream repository, you would usually fork it first, clone your fork, and then submit a PR from your fork.
                              Scenarios Where Forking is Particularly Useful
1. Contributing to Open-Source Projects
   2. Experimenting with a Project
3. Maintaining Custom Versions
 4. Learning and Contributing to Code
 5. Developing Features Independently
  6. Working on Projects with No Write Access
                                      = Advantages of Forking
-Safety: Forking allows you to make changes without affecting the original project. You can experiment, fix bugs, or add features without risking the stability of the main codebase.
-Collaboration: Forking is a great way to collaborate with others on open-source projects. You can propose changes (through pull requests) and improve the project incrementally.
-Contributing to Open-Source: Forking is the primary way most contributors participate in open-source projects. It’s a straightforward way to contribute to a project, especially when you don’t have direct access to the main repository.
-Learning: Forking allows you to explore and learn from other people’s code. You can experiment and build your own version of the project to better understand how it works.
                             Disadvantages of Forking
.Fragmentation: If too many changes are made in a fork without being merged back into the main repository, it can lead to fragmented development. Keeping forks up to date with the main project requires effort.
.Maintenance Overhead: If the upstream repository is very active, keeping your fork synchronized with the latest changes from the original repository can be challenging and time-consuming.
.Contributions May Be Ignored: Just because you fork a repository and submit a pull request doesn’t mean it will be merged. Maintainers may not accept all changes, especially if they don't align with the project’s goals.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
                     How Issues Help in Tracking Bugs and Managing Tasks:
-Bug Tracking: When a bug is discovered in the code, it can be created as an issue. The issue will detail the nature of the bug, how to reproduce it, expected behavior and any other relevant information . This makes it easier for team members to identify and resolve issues systematically.
-Task Management: Issues can be used to track tasks that need to be completed. These could be features to be implemented, improvements to be made, or tests to be written. Each task can be assigned to a specific team member and deadlines or milestones can be set to help with prioritization and tracking progress.
-Feature Requests: Issues are also useful for tracking feature requests. If someone in the community or the development team suggests an improvement or new feature, an issue can be created to capture the request, discuss its feasibility, and decide if and when it should be implemented.
             How to Use Issues Effectively:
Descriptive Titles and Clear Descriptions:
Labels: 
Assignees: 
Milestones: 
Comments and Collaboration
               How Project Boards Help in Managing Tasks and Improving Project Organization:
-Visualizing Workflow: 
-Tracking Progress: 
-Organizing Work by Categories:
-Linking Issues to Boards
                      How to Use Project Boards Effectively:
1 Create Boards for Different Purposes: 
2 Use Automation
3 Set Priorities:
4 Collaborate and Review: 
              Examples of Using Project Boards:
-Development Workflow: A team creates a project board for managing the development of new features. They create columns such as Backlog, In Progress, Code Review, and Done. Each feature or bug is represented as a card that moves through these columns as it progresses through the development cycle.
-Release Planning: A team uses a project board to organize tasks leading up to a software release. The columns might include Milestone 1 (Features), Milestone 2 (, and Milestone 3, with tasks moved between columns as the project progresses. This allows everyone to see the timeline and goals for each milestone
                 =Benefits of Using Issues and Project Boards Together
-When combined, Issues and Project Boards offer powerful tools for task management and collaboration. Issues help track specific tasks, bugs, and features, while project boards allow teams to visualize and manage the overall workflow.
           How They Enhance Collaborative Efforts:
-Clear Prioritization: Issues can be tagged with labels and project boards can be used to ensure that high-priority issues are addressed first. This makes it clear what tasks should take precedence in the team’s workflow.
-Tracking Dependencies: Project boards allow teams to see which issues are dependent on others. For example, if one task is blocked by another, that can be clearly shown on the board, which helps prevent bottlenecks.
-Transparency: Both project boards and issues are visible to all team members. This transparency ensures that everyone is on the same page about what needs to be done and who is responsible for each task.


## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
1. Challenge: Misunderstanding Git Basics
. Strategy to Overcome:
         .Understand Git Fundamentals: 
          .Use Branching Effectively
   Best Practice:
-Branching Workflow
   2. Challenge: Merge Conflicts
      Strategy to Overcome:
           .Pull OfteN
      :Use GitHub’s Conflict Resolution Interface:
      Best Practice:
-Communicate Frequently
     3. Challenge: Accidental Overwriting or Loss of Changes
      strategyto overcome
         . Check Status Regularly:
        .Use Pull Requests :
        Best Practice:
-Work Incrementally
