# BDL Assessment

1. (multiple answer) Git is:

   - [x] A version control system
   - [ ] Centralized
   - [x] Distributed
   - [ ] The same as GitHub

2. (T/F) Git and GitHub are the same thing.

   - [ ] True
   - [x] False

3. (multiple choice) What is GitHub?

   - [x] A host for Git repositories
   - [ ] An integrated development environment (IDE)
   - [ ] The company that owns Git
   - [ ] All of the above

4. (fill in the blank) What is the name of the branch where the deployment-ready code is kept?

   - **master** in the past, now **main**

5. (T/F) Pull requests should be fully functional and not contain any bugs before getting teammates to look through them.

   - [x] True
   - [ ] False

6. (T/F) Git stores the history of changes made to the codebase over time, and information about who made those changes.

   - [x] True
   - [ ] False

7. (multiple choice) What is Markdown?

   - [x] A syntax for easily formatting text on the web.
   - [ ] A way to grade projects on GitHub.
   - [ ] A programming language for creating web-based applications.
   - [ ] A way to deploy code to the cloud.

8. (multiple choice) What is a commit?

   - [ ] A snapshot of all the files in the repository.
   - [x] A snapshot of just the changes from one time to the other.
   - [ ] A collection of branches.
   - [ ] Another name for a repository.

9. (multiple choice) What is a branch?

   - [x] A pointer to a specific commit.
   - [ ] A link between the local and remote histories.
   - [ ] The centralized location where repositories are stored.
   - [ ] A version of a file at a specific time.

10. (multiple choice) Which of the following commands will create a new branch?
    - [ ] `git checkout new-branch`
    - [x] `git checkout -b new-branch`
    - [ ] `git clone new-branch`
    - [ ] `git create-branch new-branch`

---

# Intermediate: Check for understanding

### Answer the following questions

1. (T/F) Staging, or `git add`, is required before creating a commit.

   - [x] True
   - [ ] False

2. (multiple choice) Which of the following commands will allow you to change branches?

   - [x] `git checkout`
   - [ ] `git clone`
   - [ ] `git add`
   - [ ] `git commit`

3. (multiple answer) What are the characteristics of a good commit message?

   - [x] Short, less than 50 characters.
   - [x] Describe the change introduced by the commit.
   - [ ] Tell the story of how your project has evolved.
   - [ ] Commit messages are optional.

4. (T/F) The command `git push` is used to grab changes from the remote repository into your local repository.

   - [ ] True
   - [x] False

5. (multiple choice) Which of the following commands will allow you to grab commits from the remote repository into your local repository?

   - [x] `git pull`
   - [ ] `git push`
   - [ ] `git checkout`
   - [ ] `git add`

6. (T/F) Merging allows you to combine changes made on one branch with the changes on a different branch.

   - [x] True
   - [ ] False

7. (multiple choice) Which of the following commands will merge `branch-a` _into_ the `master` branch?

   - [x] `git checkout master` and `git merge branch-a`
   - [ ] `git checkout branch-a` and `git merge master`
   - [ ] `git merge master` and `git checkout branch-a`
   - [ ] `git merge branch-a` and `git checkout master`

8. (T/F) Git can be used with most text editors.

   - [x] True
   - [ ] False

9. (T/F) Cloning a repository gets you a local copy of only the `master` branch.

   - [ ] True
   - [x] False

10. (multiple choice) What does the command `git branch` (without any options) do?
    - [x] Shows you a list of your local branches.
    - [ ] Creates a new branch
    - [ ] Deletes a branch
    - [ ] Renames a branch
