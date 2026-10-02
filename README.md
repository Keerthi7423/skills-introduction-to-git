# Introduction to Git

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey Keerthi7423!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/Keerthi7423/skills-introduction-to-git/issues/1)

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

Basic Git commands
Completed
100 XP
10 minutes
Git works by remembering the changes to your files as if it's taking snapshots of your file system.

Let's review a few basic commands you use to track files in your repo and save snapshots for Git to compare against.

git status
The first and most commonly used Git command is git status. It displays the state of the working tree and of the staging area (also known as the index). It lets you inspect modified, staged, and untracked files so you can decide what to do next.

git add
git add is the command you use to add file contents to the staging area.

The technical term is staging these changes. You use git add to stage new files for their first commit and to stage later changes to files Git already knows about. All changes you stage with git add are stored in the staging area until you commit them.

git commit
After you've staged some changes for commit, you can save your work to a snapshot by invoking the git commit command.

Commit is both a verb and a noun. It has essentially the same meaning as when you commit to a plan or commit a change to a database. As a verb, committing changes means you put a copy (of the file, directory, or other "stuff") in the repository as a new version. As a noun, a commit is the small chunk of data that gives a unique identity to a particular snapshot of your project. The data that's saved in a commit includes the author's name and email address, the date, comments about what you did (and why), an optional digital signature, a reference to the saved snapshot, and the parent commit or commits, if any.

git log
The git log command allows you to see information about previous commits. Each commit has a message attached to it (a commit message), and the git log command prints information about the most recent commits, like their time stamp, the author, and a commit message. This command helps you keep track of what you've been doing and what changes have been saved.

git help
Use the git help command to easily get information about all the commands you've learned so far, and more.

Remember, each command comes with its own help page, too. You can find these help pages by typing git <command> --help. For example, git commit --help brings up a page that tells you more about the git commit command and how to use it.



What is GitHub?
Completed
100 XP
8 minutes
In this unit, we review the following learning objectives:

Brief overview of the GitHub Enterprise Platform
How to create a repository
Adding files to a repository
How to search for repositories
Introduction to gists and wikis
GitHub
Before we explore the GitHub platform in detail, it's important to understand what it's built on: Git.

Git is a distributed version control system that lets developers track changes, collaborate on code, and manage revisions over time. GitHub builds on top of Git by adding collaboration tools, automation features, and a user-friendly web interface. Understanding Git basics—like commits, branches, and merging—will help you use GitHub more effectively.

A conceptual image of the GitHub Platform with layers from top to bottom: AI, Collaboration, Productivity, Security, and Scale.

GitHub is a cloud-based platform that uses Git, a distributed version control system, at its core. The GitHub platform simplifies the process of collaborating on projects and provides a website, command-line tools, and overall flow that allows developers and users to work together.

As we learned earlier, GitHub provides an AI powered developer platform to build, scale, and deliver secure software. Let’s break down each one of the core pillars of the GitHub Enterprise platform, AI, Collaboration, Productivity, Security, and Scale.

AI
Generative AI is dramatically transforming software development. The GitHub Enterprise platform enhances collaboration through AI-powered pull requests and issues, productivity through Copilot, Copilot Chat, and Copilot Agents, and security by providing quicker feedback to improve security.

Collaboration
Collaboration is at the core of everything GitHub does. GitHub offers tools that help teams work together efficiently, reducing delays and streamlining workflows.

Repositories, Issues, Pull Requests, and other tools help to support faster collaboration across roles, shorten approval cycles, and improve delivery speed.

Productivity
Productivity is accelerated with automation that the GitHub Enterprise Platform provides. With built-in CI/CD (Continuous Integration and Continuous Delivery) tools directly integrated into the development process, the platform lets users automate repetitive tasks and speed up daily work. This allows developers to focus more on coding and solving problems.

Security
GitHub integrates security directly into the development process from the very beginning and at every stage. GitHub Enterprise includes native, first-party features like CodeQL, secret scanning, Dependabot, and security overview to minimize risks. Code remains private, while still benefiting from integrated security checks.

GitHub continues to invest in enterprise-grade security and compliance. Trusted by Microsoft and organizations in highly regulated industries, GitHub adheres to global compliance standards, making it a reliable choice for secure development at scale.

Scale
GitHub is the largest developer community of its kind, with real-time data from over 100 million developers, 420 million repositories, and countless deployments. GitHub continuously learns and evolves its products. Its large user base provides a diverse perspective on what developers need, driving ongoing innovation to meet those needs. At the same time, GitHub is an extensible platform—open source developers from around the world contribute to and enhance the very features that make GitHub exceptional.

This has translated into an incredible scale that is unmatched and unparalleled by any other company on the planet. Insights from this large developer base help GitHub continuously evolve the platform.

In essence, the GitHub Enterprise Platform focuses on the developer experience. It provides collaboration tools, automation, and AI-driven features that support productivity, security, and scalability in a unified developer experience.

Now let’s get into the backbone of GitHub, repositories.

Introduction to repositories
Let’s first review:

What is a repository?
How to create a repository
Adding files to a repository
How to search for repositories
Introduction to gists, wikis, and GitHub pages
What is a repository?
A repository contains all of your project's files and each file's revision history. It's one of the essential parts that helps you collaborate with people. You can use repositories to manage your work, track changes, store revision history, and work with others. Before we dive too deep, let’s first start with how to create a repository.

How to create a repository
You can create a new repository on your personal account or any organization where you have sufficient permissions.

Let’s walk through how to create a repository from github.com.

In the upper-right corner of any page, use the drop-down menu, and select New repository.

A screenshot of the drop-down menu of the plus sign in the top right corner of GitHub.com, with the first option being New repository.

Use the Owner drop-down menu to select the account you want to own the repository.

A screenshot of the drop-down menu of who should be the owner of the new repository.

Type a name for your repository, and an optional description.

An image of the text box of the repository name highlighted.

Choose a repository visibility.

Public repositories are accessible to everyone on the internet.

Private repositories are only accessible to you, people you explicitly share access with, and, for organization repositories, certain organization members.

Select Create repository and congratulations! You just created a repository!

How to clone a repository
Cloning a repository allows you to create a local copy of a repository on your computer. This is useful for making changes locally and syncing them back to the remote repository.

On GitHub.com, navigate to the main page of the repository you want to clone.

Above the list of files, click the Code button.

Screenshot of the Code button dropdown menu with clone options.

Copy the URL for the repository using the HTTPS, SSH, or GitHub CLI option.

Open your terminal and navigate to the directory where you want to clone the repository.

Run the following command, replacing <repository-url> with the URL you copied:

Bash
git clone <repository-url>
Once the cloning process is complete, navigate into the repository folder:

Bash
cd <repository-name>
Congratulations! You now have a local copy of the repository.

Next up, let’s review how to add files to your repository.

How to add a file to your repository
Files in GitHub can do a handful of things, but the main purpose of files is to store data and information about your project. To add a file to a repository, you need at least Write access.

Let’s review how to add a file to your repository.

On GitHub.com, navigate to the main page of the repository.

In your repository, browse to the folder where you want to create a file by selecting the creating a new file link or uploading an existing file.

Once added, above the list of files select the Add file ᐁ drop-down menu. Then select Create new file.

A screenshot of the option to add a file to your new repository highlighted in red with the add file button towards the right of the screen.

In the file name field, type the name and extension for the file. To create subdirectories, type the / directory separator.

In the file contents text box, type content for the file.

To review the new content, above the file contents, select Preview.

Screenshot showing a yml file with the preview button highlighted in the top left.

Select Commit changes.

In the Commit message field, type a short and meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message.

Below the Commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, you should choose to create a new branch for your commit, and then create a pull request.

Screenshot showing creating a new branch from a commit option select with the textbox of the new branch below it.

Select Commit changes or Propose changes.

Congratulations, you just created a new file in your repository! You have also created a new branch and made a commit.

Before we review branches and commits in the next unit, let’s quickly review gists, wikis, and GitHub pages because they're similar to repositories.

What are Gists?
Gists are a feature of GitHub that allows users to share code snippets, notes, or other small pieces of information in a lightweight and convenient way. They are essentially mini Git repositories, which means you can fork, clone, and version-control them just like a full repository. Gists are particularly useful for sharing quick solutions, configuration files, or examples without the need to create a full repository.

Key Features of Gists:
Public and Secret Gists:

Public Gists: These are visible to everyone and can be discovered through GitHub's search functionality. They are ideal for sharing code snippets or solutions that you want to make available to the broader community.
Secret Gists: These are not searchable or publicly listed, but they are not entirely private. Anyone with the URL can access them. They are useful for sharing code with a limited audience, such as collaborators or friends.
Version control:

Every change made to a gist is tracked, allowing you to view the history of edits. This makes it easy to revert to a previous version or see how the snippet has evolved over time.
Forking and cloning:

Like repositories, gists can be forked and cloned. This allows others to build upon your work or adapt it to their needs.
Embedding:

Gists can be embedded into websites or blogs, making them a great tool for sharing code examples in tutorials or documentation.
Markdown support:

Gists support Markdown formatting, which means you can include rich text, headings, links, and even images alongside your code. This is particularly useful for adding context or explanations to your snippets.
Collaboration:

While gists are typically used for individual snippets, they can also be shared and collaborated on by multiple users. Forking and commenting on gists enable lightweight collaboration.
Use cases for Gists:
Sharing quick code examples or solutions.
Storing configuration files or scripts for personal use.
Creating templates for commonly used code patterns.
Sharing error logs or debugging information with others.
Embedding code snippets in blogs, forums, or documentation.
 Important

Never use gists to store sensitive or confidential data, such as passwords, secrets, or API keys—even in scripts or config files.
Gists are not fully private: even secret gists can be accessed by anyone with the link. Always review your content carefully before sharing.

Limitations of Gists:
Gists are not entirely private, even if marked as secret. Anyone with the URL can access them, so they should not be used for sensitive or confidential information.
They are best suited for small snippets or single files. For larger projects or multi-file structures, a full repository is more appropriate.
To learn more about how to create and manage gists, refer to the GitHub documentation in the Resources section of this module or visit the GitHub Gists documentation.

Forking and cloning Gists
You can fork a gist to create a copy of someone else's gist in your account.

Navigate to the gist you want to fork.
Select Fork at the top-right of the gist page.
To clone a gist locally:

Bash
git clone https://gist.github.com/your-gist-id.git
To learn more about gists, see the linked article in our Resources section at the end of this module titled Creating Gists.

What are wikis?
Every repository on GitHub.com comes equipped with a section for hosting documentation, called a wiki. You can use your repository's wiki to share long-form content about your project, such as how to use it, how you designed it, or its core principles. While a README file quickly tells what your project can do, you can use a wiki to provide additional documentation.

It’s worth a reminder that if your repository is private, only people who have at least read access to your repository will have access to your wiki.

Creating, editing, and deleting wiki pages
You can use the GitHub wiki to create and manage documentation for your project.

To create a wiki page:

Navigate to the repository.
Select the Wiki tab.
Select Create the first page if no pages exist, or New Page to add a page.
Enter a title and content, then select Save Page.
To edit a wiki page:

Navigate to the wiki page you want to edit.
Select Edit at the top-right.
Make changes and select Save Page.
To delete a wiki page:

Deleting a wiki page requires using Git. Clone the wiki repository, remove the file, and push the change.
Learn more about managing wikis in GitHub Docs - Adding or editing wiki pages.

What are Feature Previews?
Feature Previews allow you to try out experimental features on GitHub before they are officially released. These previews give you early access to new functionality and allow you to provide feedback to help shape the final product.

To enable or disable a feature preview:

Navigate to your GitHub account by selecting your profile picture in the top-right corner of GitHub.com.
Select Feature preview from the drop-down menu.
Browse the list of available previews and toggle the features you want to try.
Feature Previews are a great way to stay ahead of the curve and explore new tools that can enhance your GitHub experience.


Components of the GitHub flow
Completed
100 XP
8 minutes
In this unit, we're reviewing the following components of the GitHub flow:

Branches
Commits
Pull Requests
The GitHub Flow
Git flow
Components of GitHub Flow
Before we get into GitHub-specific workflows, it's helpful to understand that GitHub Flow builds directly on Git’s foundational concepts.

Git provides tools to track and manage changes in your code over time. GitHub builds on this by making it easier to use those tools with features like branches, commits, pull requests, and visual interfaces for collaboration. Let’s start by looking at how these concepts work in GitHub.

What are branches
In the last section, we created a new file and a new branch in your repository.

Branches are an essential part of the GitHub experience. They let you make changes without affecting the default branch.

Your branch is a safe place to experiment with new features or fixes. If you make a mistake, you can revert your changes or push more changes to fix the mistake. Your changes won't update on the default branch until you merge your branch.

 Note

Alternatively, you can create a new branch and check it out by using git in a terminal. The command would be git checkout -b newBranchName

What are commits
In the previous unit, you added a new file into the repository by pushing a commit. Let’s briefly review what commits are.

A commit is a change to one or more files on a branch. Each commit is tracked by a unique ID, timestamp, and contributor, regardless of whether it's made via the command line or directly in GitHub's web interface. Commits provide a clear audit trail for anyone reviewing the history of a file or linked item, such as an issue or pull request.

You can create a commit using Git in your terminal with:

git commit -m "Add a helpful commit message"
A screenshot of a list of GitHub commits to a main branch.

Within a git repository, a file can exist in several valid states as it goes through the version control process. The primary states for a file in a Git repository are Untracked and Tracked.

Untracked: An initial state of a file when it isn't yet part of the Git repository. Git is unaware of its existence.

Tracked: A tracked file is one that Git is actively monitoring. It can be in one of the following substates:

Unmodified: The file is tracked, but it hasn't been modified since the last commit.
Modified: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.
Staged: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.
Committed: The file is in the repository's database. It represents the latest committed version of the file.
These states help your team understand the status of each file and where it is in the version control process.

What are pull requests?
A pull request is the mechanism used to signal that the commits from one branch are ready to be merged into another branch.

The team member submitting the pull request asks one or more reviewers to verify the code and approve the merge. These reviewers have the opportunity to comment on changes, add their own, or use the pull request itself for further discussion.

GitHub also supports Draft Pull Requests, which let you open a pull request that's not yet ready for review.

Once the changes have been approved (if required), the pull request's source branch (the compare branch) is merged into the base branch.

A screenshot of a pull request and a comment within the pull request.

Now that you’ve seen how branches, commits, and pull requests work, let’s walk through how they come together in GitHub Flow.

The GitHub flow
Screenshot showing a visual representation of the GitHub flow in a linear format that includes a new branch, commits, pull request, and merging the changes back to main in that order.

The GitHub flow is a simple workflow that helps you safely make and share changes. It’s great for trying out ideas and collaborating with your team using branches, pull requests, and merges.

 Note

GitHub flow is one of several popular workflows. Others include Git flow and trunk-based development.

Now that we know the basics of GitHub we can walk through the GitHub flow and its components.

Start by creating a branch so your changes, features, or fixes don’t affect the main branch.
Next, make your updates in the branch. If your workflow supports it, you can deploy changes from this branch to test them before merging.
Now, open a pull request to invite feedback and begin a review.
Then, review the comments and make any necessary updates based on your team’s feedback.
Finally, once you’re confident in your changes, get approval and merge the pull request into the main branch.
After that, delete the branch to keep your repository clean and avoid using outdated branches.
Git flow
While GitHub Flow is a lightweight workflow designed for continuous delivery, Git flow is a more structured branching model often used in release-driven environments. Git flow has been around longer than GitHub Flow, and you may still see the term master used instead of main as the default branch.

Nvie's diagram of a Git branching model showing feature branches, a develop branch, release branches, hotfixes, and the master branch over time. Colored commit nodes and arrows illustrate how features are merged into develop, how release branches are created for version 1.0, how bug fixes flow back into develop, and how hotfixes are applied directly to master. Tags mark releases 0.1, 0.2, and 1.0.

Image by Vincent Driessen, from 'A successful Git branching model'

Git flow Branch Types
Git flow uses several long-lived and temporary branches:

master: Always reflects production-ready code.
develop: Contains the latest development work for the next release.
feature/*: Used to create new features; branched from develop and merged back when complete.
release/*: Prepares a new production release from develop; allows final testing and minor bug fixes.
hotfix/*: Used to quickly patch production issues; branched from master.
How the Git flow Process Works
Developers create feature branches from develop to build new functionality.
When it's time for a release, a release branch is created from develop. This isolates release preparation work so development can continue uninterrupted.
Bug fixes can be added to the release branch, but major features should wait for a future release.
Once ready, the release branch is merged into master and tagged with a version number. GitHub can use these tags to help you generate release notes.
The same release branch should be merged back into develop to keep it in sync.
If a critical production bug arises, a hotfix branch is created from master. Once fixed, it’s merged into both master and develop.
When to Use Git flow
Best suited for projects with scheduled or versioned releases
Helpful if you maintain multiple production versions (e.g., long-term support branches)
Ideal for slower, more structured development cycles (e.g., enterprise or regulated environments)
Considered more "heavyweight" than GitHub Flow due to additional branch management
 Note

Git flow assumes merge commits for integrating branches. Using rebase or squash merges can interfere with its branch structure and history tracking.

For many teams using GitHub, GitHub Flow is simpler and faster. But if your team values predictability and needs more release planning, Git flow may be a better fit.

Congratulations! You’ve just walked through the full GitHub Flow—and explored how Git flow offers a structured alternative for release-driven projects.

Let’s move onto the next section where we’ll cover the differences between issues and discussions.
