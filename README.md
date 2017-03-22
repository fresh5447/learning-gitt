# GitHub Step-by-step

__For a new project:__
Create repository in GitHub
Then from the command line we:
1. `git init`
2. `git add -A` //adds all files to your repository
3. `git commit -m “first commit”`
4. `git remote add origin <URL>` (copy and paste the URL from your new repo page on GitHub)
5. `git push -u origin master`

----

__Existing project__
1. `git status` //reminds you of what files you have already committed and what needs to be committed
2. `git add -A` //preparing to save changes made to all files
3. `git commit -m "some msg"` //adds message to your commit, where you can tell yourself what you accomplished since last commit(BE SPECIFIC)
4. `git push origin master` //Hooray! You have saved your project changes to the cloud!


----
To pull code from your Github repository, into your local code base:
`git pull origin master`
