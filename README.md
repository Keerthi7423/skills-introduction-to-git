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

