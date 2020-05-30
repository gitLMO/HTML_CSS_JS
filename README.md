# HTML_CSS_JS
CMDs to plublish code to github and to publish to git hub pages for the world to see

copy repository to local: copy button next to URL link from Setting> scroll down: 
ere, will see only the Readme.md)
git status		(see which branch you are in, defaults to master
we want to work on gh-pages so check this one out:
git checkout gh-pages 
git status (should be "on brnch gh-pages')
dir (to list files)
-- can delete what is there, or create a new directory/folder
mkdir site
cd site > dir (nothing there)
--open editor, create and save as: index.html
...
git add . 		(mark to save/commit. use "." to mark entire folder)
git add site/index.html

git commit -m 	(save changes in local + m x message - required ex. "My first page")
git push		(update remote)

# tips
----- To create a new branch and switch to it at the same time, you can run the git checkout command with the -b switch:
$ git checkout -b iss53
Switched to a new branch "iss53"
----- This is shorthand for:
$ git branch iss53
$ git checkout iss53

# from tutorial: https://git-scm.com/docs++++
# cheat sheet++ https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf
# create a new repository on the command line
echo "# LiDAR" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/gitLMO/LiDAR.git
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/gitLMO/LiDAR.git
git push -u origin master
