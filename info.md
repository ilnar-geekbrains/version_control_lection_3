<Links>

[GitHub]: https://gist.github.com/Jekins/2bf2d0638163f1294637
[Markdown Guide]: https://www.markdownguide.org/basic-syntax/
[Git]: https://git-scm.com/
[Video]: (https://boosty.to/ksergeyru/posts/35a120e5-3219-44c4-9448-e2cc26b4325a)
[Visual learning]: (https://learngitbranching.js.org/?locale=ru_RU)

<Link for table of Content >

[Beginning in Git]:#Beginning-in-Git
[Work with Git]:#Work-with-Git
[Info about commits]:#Info-about-commits
[More info]:#More-info

![gitImg](https://fuzeservers.ru/wp-content/uploads/3/0/c/30c29ce4cc08523ecc6e1f205bc207d0.jpeg "Git")

# About Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 


# Info about commands  of Git
## Content
1. [Beginning in Git]
2. [Work with Git]
3. [Info about commits]
4. [More info]

## Beginning in Git
* `git config --global user.name "yourName"` - input your name
* `git config --global user.email "exampel@exampel.com"` - input your e-mail
>*This is necessary to indicate in commit the information about the user who edited the file.*
* `git init` – initializing the local repository

## Work with Git
* `git add` – add a file or files to the next commit
* `git commit -m "message"` – creating a commit
* `git status` – get information from git about its current state

## Info about commits
* `git log` – displaying the history of all commits with their hash codes
* `git diff` – check difference between current file an file from commit

## Get file contents from commit

* `git checkout` – change file contents from some commit
* `git checkout master` – back to last file status

## Get file contents from commit
* `git checkout` – change file contents from some commit
* `git checkout master` – back to last file state


## Work with remote repository

* `git push` - update remote refs along with associated objects
* `git pull` - fetch from and integrate with another repository or a local branch

## More info
[Git] - official page  
[GitHub]; [Markdown Guide] - learn more  
[Video] - about installation git  
[Visual learning] - site or learning