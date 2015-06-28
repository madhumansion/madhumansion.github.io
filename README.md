# madhumansion.github.io
Madhu Mansion Charitable Trusti

## todo:

1. Changing the website layout (tbd)
2. Refactor (@amarendra)
3. Add further todos:

-- change this file and make a pull request (on github) and I will merge it to the master.

Note cum warning: please do not use web interface for editing files from "master" branch". Use your own github.com account to checkout the files (preferably in a new branch).

Basic steps:

1. Install git on your local machine
2. Setup gitconfig using your name and email (https://help.github.com/articles/set-up-git/ for step 1 and 2 and maybe beyond)
3. run "git clone https://github.com/madhumansion/madhumansion.github.io.git" in your code/workspace/projects/whatever/blah directory
3. You will have a directory with latest `master` branch code named `madhumansion.github.io` - this is the root directory of this project or repository
4. Now run `git branch` in the root folder, you are on master branch and you don't have to be there.
5. Run `git checkout -b "your new branch name"` - keep branch name short, descriptive and unique.
6. Now you have everything that was in `master` in your new branch, let's call it `new-branch`
7. Start modifying files in whatever editor or IDE you want. One you are finsihed or do it regularly to keep track of changes you have made - run `git status in root repo folder
8. You will see the changes and if the files changed are okay, run `git add *` it will stage the files for commit
9. Then run `git commit -m "Your commit message which is a short commit description"`
10. When you are commits that you want to be saved (pushed to origin), run `git push origin new-branch` and your changes will be pushed to the remote orgin (i.e. github origin in your branch and it won't mess with master or anyone else's code)
11. If you think it was a feature addition or somehting that should be live on tthe webite - make a pull request to master branch or someone's branch who is supposed to merge changes to master branch

If you find these steps confusing then ask others or go here: https://try.github.io/ and/or https://git-scm.com/book/en/v2/Getting-Started-Git-Basics (I am learning myself so I am sure a lot of the above mentioned is confusing and incorrect possibly)  
