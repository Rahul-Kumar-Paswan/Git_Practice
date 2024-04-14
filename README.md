# 
    Git (VERSION CONTROL SYSTEM)

## **Introduction**

### **What is Git?**

Git is a distributed version control system widely used for tracking changes in source code during software development. It allows multiple developers to collaborate on projects by providing mechanisms to manage and merge changes efficiently. Git stores the entire history of a project, enabling users to revert to previous versions, compare changes, and branch off to work on new features independently. It's known for its speed, flexibility, and robustness, making it a cornerstone tool in modern software development workflows.

![](https://lh7-us.googleusercontent.com/0BGjnZ1jyFaInFU5egr3ETmivh-FffepG8nh4wqb_ArQr9yAQgW4uva8pIjspbt0TJvTzJ3kRQf-e2eh-7FNJ2YN6hgizjIHC1u2Xu18OWUcbsmcfTxJTCAM546UZAqexffaqVfFjBTdYJL9HBSY6mI)

### Why Use Git?

1. Version Control: Git tracks changes made to files over time, allowing developers to revert to previous versions if needed. This feature ensures that the entire history of the project is preserved.
2. Collaboration: Git enables multiple developers to work on the same project simultaneously. Each developer can work on their own branch, making changes independently, and then merge their work back into the main branch when ready.
3. Branching and Merging: Git makes branching and merging of code effortless. Developers can create separate branches to work on specific features or fixes without affecting the main codebase. Once their work is complete, they can merge their changes back into the main branch.
4. Distributed Development: Git is a distributed version control system, meaning that each developer has a local copy of the entire repository. This allows developers to work offline and then synchronize their changes with a central repository when they're back online.
5. Traceability: Git provides detailed logs of changes made to the codebase, including who made the changes and when. This traceability helps in debugging issues and understanding the evolution of the codebase over time.
6. Backup and Disaster Recovery: By using Git, developers have a reliable backup of their codebase. Even if a developer's local copy is lost or corrupted, they can recover the code from the central repository.
7. Open Source and Community Support: Git is open source and has a vast community of users and contributors. This means there are numerous resources, tutorials, and tools available to help developers learn and use Git effectively.

**Getting Started**

**Installing Git**

Download Git: If Git is not installed, you can download the installer for your operating system from the official Git website:[ https://git-scm.com/downloads](https://git-scm.com/downloads)

Verify Installation: After the installation is complete, open a terminal or command prompt again and type:

git --version

![](https://lh7-us.googleusercontent.com/yCV1oSgXDBe-_1pzs7BErM_EcbBOO6ornkIxu0Y21YM1cJUfEj0m3UKXqakau0xWxbBpwZFgRh2BmQ-7FII26GXHQbmVploxuKR9BfOGVe1k-BHjzRjiW3tbFlUgDdvdkEKC7-JkTsdc-sSLlcJsHd8)

This command should now display the Git version number, confirming that Git has been successfully installed.

Configuring Git

After installing Git, you may want to configure your username and email address, which will be associated with your Git commits. You can do this by running the following commands in the terminal or command prompt:

git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"

![](https://lh7-us.googleusercontent.com/MI2GDRbu-ZtwEG2_pthoPVKoW-8EoQhK4vrV2K0A8WYuACQ5J5foWGJwQVeM6oRWgTQXu1MBTFC6MeLGYP5dMc_15sTFrVnEBLizbtG4sUo43B2Y0It1kSfX3gmxS9oSpE218QQvPMUOuOke2j7YKJM)

This command will display all global configuration settings for Git on your system.

git config --global --list

![](https://lh7-us.googleusercontent.com/NDr2hqS99I1oI_RiqaoWUZG5iBL-hE5lbZh_BhshDRAGx0oz-FmjqlI1P3I2UqRQh0D2u8uM8G8Yt5doq0NZjg07rrys0KfzW3WmYcUHAElLxSNpDxtGyM-xCWRvVDyP-CzyBfDdlcpAfLx_rRiSIjQ)

Initializing a Repository

Initializing a repository refers to the process of setting up a directory as a Git repository, thereby enabling Git to start tracking changes to files within that directory.

When you initialize a repository, Git creates a hidden subdirectory within the directory called ".git". This subdirectory contains all the metadata and configuration files that Git uses to manage the repository, including information about commits, branches, tags, and remote repositories.

You should initialize a repository in a directory when you want to start using version control for the files within that directory. Here are some reasons why you might want to initialize a repository.

Before Initializing a Repository

![](https://lh7-us.googleusercontent.com/Wod80OY-OAXpAP58ILCELKMT5XmDEYiGyj9afvWVFMvelPuwmHu60S8SE51dMXUjWvDfvOzslfmlh1UYqK6VQt0NoUrzm4DHXdE4JoHLcghghrkFj_ZsgiC8FVOwxp8kqstii_DRlM4SpbKBqV3WcPs)

After Initializing a Repository

git init

![](https://lh7-us.googleusercontent.com/6Ayvjhzq2rW6hbTzti6Ks8nsLT94RVb-WkyHUDQdXewdO607K8mR1T-5H_cOP5ni3NrO_8iVOx4lTDGcCvyty7px_axqRs-IC5fM6VocHsFejkPH5C0hW5RlLYY2g7LqnOyU413XZzb7IlTVLnVTmOA)

GitHub Integration

Creating a Repository

Log in to your GitHub account.

Click on the "+" icon in the top-right corner and select "New repository." Enter a name for your repository.

Click the "Create repository" button to finalize the creation of your new repository.

![](https://lh7-us.googleusercontent.com/nj8jiVWlNVzf2_IpJgi54_X-ygp1uRQokZWuLCIOwVVm1_SZahpMQxX8dWDRpIEabg2tntrLWLFs3LDFm3EmraC0c6kxIOcxeK1ompK4oJ3ihiSnLgAQGmKzRFIBoyysgMrP-FsajfZ1PGSEaGp_2iU)

Basic Git Commands

Before starting to work with a Git repository on your local machine, it's essential to establish a connection between your local environment and the remote repository hosted on GitHub.

Check Existing Remotes: It's good practice to verify if any remote repositories are already linked to your local Git project.

git remote -v

This command will list any existing remote repositories and their corresponding URLs.

![](https://lh7-us.googleusercontent.com/w87QdYXXZIsfuqYMirpTSvaCmQaQBuSpud2WILjnO1a6UoArf2U-PYm2VoRrkSTaqIHz6_6ZnGH0ltZvzdtC4AQ2YLjPlsxazQWUvRgqTnNXLbEISZorV3yoIvElJYOskC9ESSRnW-9zcFoctUa04yg)

Connect to Remote Repository: If no remote repository is currently linked or you need to connect to a new one, you can do so using this command.

### git remote add `<remote-name>` `<remote-url>`

git remote add origin `<repo-link>`

![](https://lh7-us.googleusercontent.com/zPZMVCkd8TCNU7MPWzT0oMjRNOTJPScFuaO6rwxlJBJM7vXK9K6zDyy-_iWyTJ7kvri2RS2dJxL-WfC1mCus5zCD4XzC0pmYloYiBO25DhP_rk4cvtDu-cxyCteGSQwGBtlify43WI34Ystg03RuUZE)

Change Remote Repository :

If you need to change the remote repository URL later, you can use the following command, replacing ‘new-repo-link’ with the URL of the new repository:

git remote set-url origin new-repo-link

Rename the remote: If you want to keep the existing URL but change the remote name, you can use git remote rename <old_name> <new_name>.

Delete and re-add: If you need to completely remove and re-add the remote with the new URL, you can use git remote remove origin followed by git remote add origin <new_repo_link>.

![](https://lh7-us.googleusercontent.com/IYXtS7N87kx5AukEyxGnx9k1PiNVelO5Di_7AVlWxAZGPW3qv5l-fmRgs_ddOFfJrWQREQEbTGO6JuDSlqum_OiI3RghLb4o3Zp8VjyAvuikEnQbJ-wW6KIGHf9R0ST3U98Wm_K_nQWIzVu-qR8-qfM)

Working Directory: The working directory is the directory on your local machine where you're actively working on your project. It contains all the files and directories associated with your project. When you make changes to files in this directory, Git detects these modifications as "unstaged changes."

Staging Area (Index): The staging area is an intermediate area between your working directory and your local repository. It's essentially a snapshot of your working directory at a particular point in time. When you modify files in your working directory, you can selectively choose which changes to include in your next commit by adding them to the staging area. This allows you to review and organize your changes before making them a part of your project's history.

Local Repository: The local repository is where Git stores all the committed changes and project history on your local machine. When you commit changes from the staging area, they are saved in the local repository, and a new commit object is created with a unique identifier (hash). This allows you to track the history of your project and revert to previous states if needed. Each Git repository typically consists of a working directory, a staging area, and a local repository.

Remote Repository: The remote repository is a version of your project hosted on a remote server, such as GitHub, GitLab, or Bitbucket. It serves as a centralized location where multiple developers can collaborate on the same project. You can push your local commits to the remote repository to share your changes with others, and you can also pull changes from the remote repository to update your local copy with the latest modifications made by other collaborators. The remote repository acts as a backup and a centralized hub for collaboration in distributed version control systems like Git.

git status: Show the current status of the repository, including tracked/untracked files and changes to be committed.

![](https://lh7-us.googleusercontent.com/KTPfQ9eLBcWCX5xTTNdeivSMG76J3XLWVsPyLK4327dXNoMrGMSjJqMNfblTrMEOZZa-bmmdomSBgIoWUGQtL5g1-Bzn8UVTclPFB9__syQoUJ25f4tnf8YxUfJFl07Os2eI2fUyVZLOW9S6N_Zi4rk)

Create a file main.py

![](https://lh7-us.googleusercontent.com/taxJaz8Yxe627oe5htSi96-5sWozAxupPk2ALbZV-ZCLL6FrJfv4v-4-KTuMMhkE10X-QiFWvWK5xuiEkpj2YOQ4AaBy-mSw3UueaCFlBAf3FeZr-5F2h3qHfl7KJl0n21GgQpeO_LVWhWuAATM2iAA)

After creating a new file, main.py, Git recognizes this as an untracked file. It means Git is not currently monitoring changes in this file.

![](https://lh7-us.googleusercontent.com/i3nTKgqCIGm2v0LFCYXkyyFUWgatCujqisXog9EmCcbn552kyVyKQVHK2xJv1lwMVaHSAdlPFJ5yd8g1JwW6yFwpJklq76E5SdXe9OKqwzTNyWQGsc307Q4doydWt-FrhEIJBlf3eVgEtYmZZlWP7fQ)

Running git status again, you'll notice that main.py appears under the list of "untracked files." This indicates that Git acknowledges the existence of this new file but hasn't yet started tracking its changes.

git add [file]: Add a file to the staging area. You can also use git add . to add all files in the current directory.

![](https://lh7-us.googleusercontent.com/R7OphLtTqm2YV5UfvlobGua3BFSjBNP7OkRumaGCxifnju4FjFeyoHUvkGP2TRvvC2b76k6gyPVWu5vHIAQOifM8cBoF2db5braeWKxSk13FnsJpT7OXMtA_KDt7R9Su16igHucFxe2_EuI9K6NTYpc)

running git status again will reflect that main.py has transitioned from being an untracked file to a tracked file. This means that Git is now monitoring changes in main.py, and any modifications made to it will be included in the next commit.

git commit: Commit staged changes with a descriptive message.

git commit -m “commit message”

![](https://lh7-us.googleusercontent.com/8fA-RcqXvpUpbKBbHyQmssWiQlGqLqBHgZe7TxsgdoSVZsEEbdX1rs9jxYSPaGkFwngP2aA_hJJ8KMxvZrYcGsLMg0sbBkXrMdmOoqsEXq9sc3Fi56HJ95QUzPtw-_bOLfgwa0s2fMUJ49q1NrmUjKM)

After executing the git commit command with a descriptive message like git commit -m "first commit", the staged changes are committed to the repository. This means that the changes you added to the staging area using git add are now permanently stored in the version history of the repository.

You can verify this by using the git log command, which displays a chronological list of commits, including the latest one you just made.

![](https://lh7-us.googleusercontent.com/zhmXmANwphKV9FxA991q_JqYpTJ6FrQzyGrnaY0db4iY29fgi9BG4q14cBa2DsgFY6FLcFOgtVZ147XdxoiikoYMGFi5DEV-gnbc5DBhDH463KT4Q_OlJAd6uYkiJK3PQC83K4qwuWJHG0Znpl9pdek)

Upon running git status again after the commit, you'll observe that there are no longer any changes staged for commit. Git will inform you that the working directory is clean, indicating that all modifications have been committed to the repository.

![](https://lh7-us.googleusercontent.com/fCOT-xf4nUbYh9SjvqSnTHANsL0Wg8DvlfIc9rIyBJdzzE2fRvjOND0lXG9XLl-znfCE0YQgBiAXR6W44M2xfFzJf1mYatW1Y7J4qILrYWjwMvDo-3vvtMKenPdjWA77zLIY763iq1X4ZKweus3Kj20)

git push: Upload local repository content to a remote repository.
git push -u origin `<branch name>`
Using git push -u origin `<branch name>` allows you to upload the content of your local repository to a remote repository. This command ensures that your local changes are synchronized with the remote repository, making them accessible to collaborators.

Upon executing this command, you'll observe that your files are transferred to the remote repository, making them available to others who have access to the remote repository.

![](https://lh7-us.googleusercontent.com/C0WzME4_WHOue8VlmfF5Vb2sv-yI5NFBM_RL20ScMgHnNHKOfksDfcCGR6G1l2Mh51KFnSj5MvTpDfxCcVAlVF138MUeg7wBi-dJHRwGNlqe1TalncBbadWUAhEgOVc6ki5l_o5tug0-OtOELUF7VNw)

Branching

Git branching is a powerful feature that allows you to diverge from the main line of development (usually called the “master” or “main” branch) and work on different features, fixes, or experiments in isolation.

What is a Branch?:

    - A branch in Git is essentially a lightweight movable pointer to a commit. Each branch represents an independent line of development within a repository.

    - The main branch, often named`master` (though it's common now to use `main`), is the default branch that typically represents the stable version of the project.

![](https://lh7-us.googleusercontent.com/mcI_mVAO9tV9d59xoVn8YBUTllHgU0_OU1RFbfkruGEaV06orDf5tuSeSTsF3Qp48u5-8fUtqnpf19rMA_tZEjvfSNo-jTPom8aGe4fpkFpGhC5ZFD1K_hhvGqNA08zUsN7Wz1lH4VdD-cDHivGN3Z0)

Creating a Branch:

    - You can create a new branch using the`git branch <branch-name>` command. This creates a new branch pointing to the same commit as the current branch.

    - Alternatively, you can use`git checkout -b <branch-name>` to create a new branch and switch to it in a single command.

Switching Between Branches:

    - You can switch between branches using the`git checkout <branch-name>` command. This updates the working directory to match the version of the project stored in the specified branch.

Working on a Branch:

    - Once you're on a branch, you can make changes to your project just like you would on the main branch (`master` or `main`).

    - These changes are isolated to the specific branch you're working on, allowing you to work on multiple features simultaneously without affecting the main branch.

Committing Changes:

    - After making changes on a branch, you can commit them using`git commit`. These commits are unique to the branch and do not affect other branches until you merge them.

Deleting Branches:

    - After you've finished working on a branch and merged its changes into the main branch, you can delete the branch using`git branch -d <branch-name>`. This removes the branch from your local repository.

    - Use`git push origin --delete <branch-name>` to also delete the branch from the remote repository.

Merging Branches:

    - Merging is the process of combining changes from one branch into another. You can merge a branch into another branch using`git merge <branch-name>`.

    - When you merge a branch into another, Git integrates the changes from the source branch into the target branch, creating a new merge commit if necessary.

Resolving Conflicts:

    - Conflicts may arise during the merge process if changes conflict with each other. Git will prompt you to resolve these conflicts manually by editing the affected files and choosing which changes to keep.

![](https://lh7-us.googleusercontent.com/nnbkWRJM0Fy0C-SOSxPVbVD2X0sEZzY4Ww0mvVVT479Cb3TSXqgetUqlBq4YptSCzhF8j4yM9J1xs9RsP6ExmNrfWXsk8zolD-NkVBm-IboTK4yZy89QKAUrp1NNMKy7DDmiSJGshfZUDvUaT_TMHKM)

![](https://lh7-us.googleusercontent.com/AMIB0VKgVegAzVb4lURs7jdu1_FiM9JsJFsr7FqmEloM0MKAdAIrKETih4AsKGKSwGr6xDqBnQpgYpqUbwfi7U_Cd6-Obs7IOYUZCJn8_Y46EfIeYbJP7PMhAyJsEfqKwC30jWLmI1enqs2ozzoDRY0)

Collaboration

Cloning a Repository

git clone: Clone a repository from a remote URL to your local machine. Simply download code to the local machine.
git clone `<repo-url>`

![](https://lh7-us.googleusercontent.com/w7Q4rNkKtafr3R_V5A6EWs4xQH2xGX4T2ETmgB6OMoxkvjlOgIxRtjsT1SKX_gdVPRAcfZscFgxpidoRKymuHH7XbkpzgK1GOJYK54YjCdB6s79MH0bV3ry8GCVypUqF18NWl8ZKbZlqxemJT0QZsWI)

After executing the command, you can confirm the successful download by using the `ls` command, which will display the newly cloned repository on your local machine.

![](https://lh7-us.googleusercontent.com/IPADf_jeVO2f0rOxZyue0QoNSuk-PeJOUvTMhJmCqInkRMVljJFBC02Oat6uPfbngladlYN48WBO0W9eKA8QrODdj-sU5wU2Ob7uxi_TxMUzS2SnZF0j_Y4-rEF2ggQQCBCymkVSKFQIxkioYtbnccc)

Pushing Changes

git push: Upload local repository content to a remote repository.
git push -u origin `<branch name>`

See above for explanation i.e on page no 10.

Pulling Changes

git pull: Fetch changes from a remote repository and merge them into the current branch.

`git pull` is a command used to fetch changes from a remote repository and integrate them into the current branch of your local repository. After fetching the changes, Git automatically merges them into your current local branch.

If there are no conflicts between the changes fetched from the remote and your local changes, Git performs a fast-forward merge, updating your local branch to reflect the changes from the remote repository. However, if there are conflicting changes, Git will prompt you to resolve these conflicts manually.

Pulling changes is essential for maintaining synchronization between your local repository and the remote repository. It ensures that you're working with the latest version of the codebase and enables seamless collaboration with other team members while preventing divergence in project history.

For instance, if your team member has made changes to the same lines of code in the repository without your knowledge, attempting to push your changes could lead to conflicts. Therefore, it's necessary to pull the changes first and merge them into your local branch to resolve any conflicts before pushing your own changes. See the below image for explanation.

![](https://lh7-us.googleusercontent.com/GjI5pdoJHbQkXi8b0hGXdDK0GDmirIshYkbG3wU3ZmA8BjZC8wwRd2b0xgFBbMqy3g_D3SLy2KLzQGsJfQEx-T4GftuIh3NVjEz8kzUGeojdfvKoAG4DpaU9VRQ2sUlRHVq4sqS2pge_Twjj5K52jOo)

Advance Topics

Rebasing

Git rebase is a powerful command used to integrate changes from one branch into another. It works by transferring commits to a new base commit, which can help maintain a cleaner, more linear project history. Here's an overview of how rebase works.

Understanding Git Rebase

Imagine you're working on a feature branch called `feature1` that diverged from the `main` branch a few commits ago. Meanwhile, other commits have been made to the `main` branch. You want to incorporate those latest changes from `main` into your `feature1` branch.

Using `git rebase`, you can "replay" your feature branch commits on top of the `main` branch commits. This process can potentially result in a more straightforward history than merging, as it creates the appearance that all changes were made in a linear sequence, even if they were originally developed in parallel.

![](https://lh7-us.googleusercontent.com/LHRPeVK5_lahd1BOTjdM1tIrX7-U2CY1qA7cXq0tYD6CJPUc7ee2svIbCtK6zFoNNlsw3iTiMl1dT2WwU8z5PXpiB1U5T_K12PeUzlFceYt0RM4yxCdLyH1zu1FVuEkLvV5fdyQzwZ_nfZd8TqHnxO0)

![](https://lh7-us.googleusercontent.com/H5P2t6yPusxc0Ju3wLZnQyYZUpvyV_r2XLG_01O-GInVH9FFNKKxL_sShoaoUiR_q1IspxwADDhgPArBzEBztlyeR0SNYSPixN9Lgz0_5hEdlRBadwScrVCmJLt65z3irMKj0o-Ihfy6Oi34dKMuSVs)

Why Use Rebase?

- Cleaner project history: Rebasing can result in a more linear and readable history.
- Avoiding unnecessary merge commits: Rebasing can eliminate the merge commits that occur when you `git merge` branches, making your project history cleaner and easier to follow.

Git diff

`git diff` is a versatile command used to show differences between various Git entities such as commits, branches, files, and more. It's particularly useful for reviewing changes before committing them, comparing branches, or examining the changes made between commits.

1. Unstaged Changes: To see the differences in files that have been modified but not yet staged, you can simply run:

   git diff
2. Staged Changes: To see what has been staged (with `git add`) but not yet committed, you can use:

   git diff --cached or git diff --staged

You can compare two commits by specifying their commit hashes:

git diff `<commit1>` `<commit2>`

![](https://lh7-us.googleusercontent.com/b58apr69oW-lGOmD84bQpnHb0ivvtvpaqNHadogXeW1wye7iissV7bEW_k8swqcmCc1CWOl8DJVrQrbjjGk257dofPn7tYVA_L0NE0zFu8Na18cFNho3rucTAJxjHdpMEs4BubyGcoA4HHHbRElT004)

To see the differences between two branches:

git diff `<branch1>` `<branch2>`

Git stash

`git stash` is a command used to temporarily shelve (or stash) changes you've made to your working directory so you can work on a different task. Your changes are saved in a stack-like structure (where you can have multiple stashes), and you can apply or remove them later. This feature is particularly useful when you need to quickly switch contexts without committing incomplete work.

1. Stashing Changes: To stash your current changes, simply run:

   git stash

![](https://lh7-us.googleusercontent.com/t5yqxjh2v-K9ZBoZT9sPp0LmnD25Snmum5OIDity-EcK4csPxiIt2BSyDAi4EuHUJ7pTAveKrXO2hGh8bBKlvmwRhEYTFlBbEDOCHV3UNwsrKjxKCpHILy0ARSk54GkwUPGlsoUEjIMeOCKTHF4Hedw)

2. Popping a Stash: If you want to apply the most recent stash and remove it from the stash list, you can use:

   git stash pop

![](https://lh7-us.googleusercontent.com/zisUgFTmxo01DvDOi2l4ks8qe0A8Xk-eS3mLmZ7Skd5KBSzT-XCUFmS9a9NLkECIy3xSjQge3bvtG0ExXLy5XQ0GPP21U-G8wRyPCsEr0Z3ASgbj-iPSgccpMA7PopdFTP4hrfnled-Hf0Hr07EZ-J0)

Git revert

`git revert` is a command used to create a new commit that undoes the changes made by a previous commit or commits. This is a safe way to undo changes, as it doesn't alter the project's history. Instead, `git revert` generates a new commit that reverses the effect of one or more earlier commits.

To revert a specific commit, you need the commit's hash ID. You can find this ID via `git log`. Once you have the commit's hash, you can revert it as follows:

git revert `<commit-hash>`

![](https://lh7-us.googleusercontent.com/u1GMcnqnWYia_i2NaHXGbSgH6b9d4rEI0fEDqE8Yh-bBXo5sRNrVYI98dJZ417qgpPmiyp3x_qCbH-ID3GOpd_Zl7RTizaKStRZIx6j0qUSNd3cRQrOR5bS7-S35mvCd7Zn984f_Cj5uhpLCBSdlKC4)

For example, if the commit hash is `abc1234`, you would run:

git revert abc1234

This command creates a new commit on top of the current branch with the changes from `abc1234` undone.

Git reset

`git reset` is a command in Git that is used to undo changes in a repository's history to a specified state. It can affect the staging area (index), the working directory, and the commit history, depending on the options used. `git reset` operates on your current branch and can change the branch's tip to a specified commit, effectively removing commits that come after it in the history.

`git reset` can be used with three different modes, which affect the working directory and staging area differently:

1. `--soft`: This mode does not touch the staging area or the working directory. It only moves the HEAD to the specified commit. Changes from the commits ahead of the reset point will be staged.

   git reset --soft `<commit>`

![](https://lh7-us.googleusercontent.com/EexhxyZhLRvq-A1SalDA21Y44lJYgOEkkvqnHfDy9ICIljV-fNOSpeJINKGUwjBtNylJpoxAD8_Kni3WPPvOQimqXd0AD_pEsTWcCheJ2YIon-KmV4kiGUd5w9AABVqB4SA6I7-0SNpUnTibfPhh_xI)

![](https://lh7-us.googleusercontent.com/atr250hobWb05lkqRB-WXHX-D8em7QzpfygxXLz2P1hUiHOzu_Rh49V7spudYTWpPrXAJwgLscxX2eQaSTAwDx4fEt1NzvZ__CrtUydLUG7sLGLMjh683d32RYx5ucKiSXwvVL23RBBNG9u7CvgZKSE)

2. `--mixed` (default): Resets the index but not the working tree. Changes are kept in your working directory but not staged.

   git reset --mixed `<commit>` Or git reset `<commit>`
3. `--hard`: Resets the index and working tree. Any changes to tracked files in the working directory since the specified commit are discarded.

   git reset --hard `<commit>`

- Undo the last commit, keep changes: To undo the last commit and keep the changes in your working directory:

  git reset --soft HEAD~1

**
