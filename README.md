# GIT Basics task

**Part 1**


1. Create account on https://github.com/ 
2. Install GIT on your workstation https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Setup git: change your global configs (add name and email, setup core text editor).
4. Generate ssh-key and integrate it with GitHub.
5. Create a new `GD_Internship` project on GitHub.
6. Clone project to your workstation.
7. Provide access for a mentor to your repository on GitHub.

**Part 2**

1. Open the git console in the `GD_Internship` directory and do the next steps.
2. Do all your experiments in the folder `task1_git_practice`.
3. Create an empty `readme.txt` file.
4. Make an init commit.
5. Create a develop branch and checkout on it.
6. Create `index.html` empty file. Commit.
7. Create a branch with the name `images`. Checkout. Add some images folder with images inside it. Commit.
8. Change your `index.html`. Add some image source inside it. Commit.
9. Go back to the develop branch.
10. Create a branch with the name `styles`. Add some styles folder with styles source inside it. Commit.
11. Change your `index.html`. Commit.
12. Go to the develop branch.
13. Merge two new branches into develop using git merge command. Resolve conflict if it appears.
14. Do not delete any branches!
15. Merge develop branch into master.
16. Checkout to the develop branch and repeat 7 items once more (use names `images2`, `styles2` for new branches). Now use the git `rebase` command for merging.  

<sub>*NOTE: As a result master/develop branches should contains all commits that were done in process*</sub>

**Part 3**

1. Try to inspect your repository with the git log command. Use different options with this command `git log --help`.
2. Push all your changes with all your branches to origin `git push origin all`.
3. Execute the command `git reflog` and save its content somewhere (not in the repository) with filename `GIT_Basics_homework.txt`.