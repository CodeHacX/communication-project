# communication-project
It is a team project.

🚩First clone a repo then work.

👉How to clone a repo?

1.On GitHub.com, navigate to the main page of the repository.

2.Above the list of files, click  Code.

3.Copy the URL for the repository.
   To clone the repository using HTTPS, under "HTTPS", click copy button.
   
4.Open Git Bash.

5.Change the current working directory to the location where you want the cloned directory.

6.Type git clone, and then paste the URL you copied earlier.

    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    
7.Press Enter to create your local clone.

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `Spoon-Knife`...

> remote: Counting objects: 10, done.

> remote: Compressing objects: 100% (8/8), done.

> remove: Total 10 (delta 1), reused 10 (delta 1)

> Unpacking objects: 100% (10/10), done.

👉How to creat pull request?
   $ git remote -v add upstream link
   (never pull node_module folder. Just create .gitignore.txt file by runing touch gitignore in git base)
1. $ git pull upstream main
2. $ git add ~A
3. $ git commit -m "comment accourding to you"
4. $ git push origin main

after this go on github repository and click on contribution option to creat pull request.

to get all data/changes in repo $ git pull upstream.
