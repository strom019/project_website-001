Step 3. Tell git you exist

Now it is time to configure your name and email. Do this by typing in the following, of course replacing the values with your own name and email.

git config --global user.name 'My_Name'
git config --global user.email 'myEmail@wherever.com'
git config --global color.ui 'auto'

-----------------------------

Step 4. Create a new directory [C:/wamp64/www/ProjectBuilding/git-training]

git init

----------------------------------
touch README.md
---------------------------

git clone /path/to/your_repository:”
git clone C:/wamp64/www/ProjectBuilding/git-training
----------------------------
git status

git add (file name here)

git status

git commit -m”Initial commit"
-----------------------example-----------
$: git commit -m "Update homepage for launch"
$: git commit -m "Fix typo in screen.scss"
$: git commit -m "Fix misspelled name on about page"
---------------------------------------------
git log
git log --oneline
---------------------------------
git config --list

In this section, you have learned to use status, log, add and commit commands to keep track of your documents in Git.
-------------------------------------------------------------

https://github.com/strom019/project_website-001.git
git remote add origin git@github.com:strom019/project_website-001.git
