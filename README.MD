# Qysh me bo setup GitBash 
Download Git nga: https://git-scm.com/downloads merreni Windows nese e keni sistemin windows dhe instalojeni ate. 

Per me verifiku qe o install bone search ne qoshin e majt ne kompjuter tek Windows Icon. Duhet me u kane qeshtu dicka:

![alt text](image.png)

#  Konfiguro email dhe username

 Hape GitBash

 Navigo te Documents duke shenuar: `cd Documents`
 
 Krijo nje folder te ri me emrin webdev: `mkdir webdev`
 
 Navigo te folderi webdev: `cd webdev`

 Konfiguro username: `git config --global user.name "Your Github username"` 
 
 Shembull username im eshte florinda-jcoders keshtu qe komanda do te duket: `git config --global user.name "florinda-jcoders"`

 Konfiguro email: `git config --global user.email "Your email associated with Github"`

 Shembull emaili im: `git config --global user.email "florinda@j-coders.com"` 

 Per me verifiku qe i ke bo hapat qysh duhet sheno: `git config --list`
 
 Duhet me ju shfaq username dhe emaili juaj.

# Qysh me bo clone projektin

Shko ne Github dhe te butoni CODE merre HTTPS link qe eshte: https://github.com/florinda-jcoders/jcoders.git

Hape GitBash dhe fute kete komand:

`git clone  https://github.com/florinda-jcoders/jcoders.git`

Kjo e ben clone projektin tek folderi juaj. 

Per me hap VS Code ne kete projekt sheno: `code .`

# Pune te mbare

# How to add your local project to Github
First navigate to the folder of your project, in our case this is in Documents/jcoders

Initialize the main branch: `git init -b main`

Add all the files to the repo: `git add .`

Commit the files: `git commit -m "First commit"`

Go to Github and create a repo, copy the HTTPS Url it should look something like this: https://github.com/florinda-jcoders/jcoders.git

We need to add this as our remote origin: `git remote add origin https://github.com/florinda-jcoders/jcoders.git`

Verify that is now your origin by typing: `git remote -v` and it should display the link. 

Now we push the changes: `git push origin main`
