Create a new repository on command Line
-----------------------------

git init

git add fileNAme

example:git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin (your git url)

git push -u origin main

git status

git remote -v(crosscheck your in gitrepo)



OR push an existing repository from the command line
-----------------------------------

git remote add origin your-git-url

git branch -M main

git push -u origin main


Hosting A site
-------------------

go to netlify website:

Netlify: Develop & deploy the best web experiences in record ...
https://www.netlify.com

succesfully signup it and login

click on new site git

1.connect to git provider

2.pick a repository

go for configure and then two options

   -select one option your convinient

    1.all repository

    2.select repository

select netlify app on github

select repository

in deploy settings choose the right branch

select the repository in netlify and gets hosted.

Note:In main direct you should have index.html to host site other wise page not found.
2.if you upadte your git repository then netlify automatically deploy the site because it has default option autoconfiguration you don't want you can disable


if you want to work on someone repository you can follow these steps 
---------------------

in cmd  go below commands

1.git clone url 

2.git remote remove  origin

3.git add url

or

fork 