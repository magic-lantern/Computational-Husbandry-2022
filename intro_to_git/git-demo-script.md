# Create a new project directory on your computer

    mkdir newproject
    cd newproject

# initialize the git repo

    git intit

# check the status of the repo

    git status

# create a file

    echo "This is a very important file." > important.txt

# check the status of the repo again

    git status

# add the file to the staging area

    git add important.txt

# check the status again

    git status

# commit the file to the repo

    git commit -m "initial commit with important file"

# add some more files

    echo "# README Files are important" > README.md
    echo "Second important analysis file" > important02.txt
    echo "another line in the file" >> important02.txt
    mkdir data
    cp ... data into the repo ... just copy a set of files into the repo

# check the status 

    git status

# add only one or two files to the staging area

    git add file1 file2

# status

    git status

# commit

    git commit

# check the commit log

    git log

# note that this log can be customized, these are specific to my ~/.gitconfig
# file

    git lg1
    git lg2

# Edit a file (make a really stupid edit)

    nvim ....

# check the diff

    git diff file

# check out the file to remove really stupid edit

    git checkout file

# edit the file with something smart, remove something and add something

    git diff
    git add file
    git commit -m "..."

# mv files into a new directory

    mkdir ....
    git mv file file
    git rm file
    git status
    git commit
    git log
    git lg1

# add files that need to be ignored...  add .log file to a directory

    mkdir compiled
    report/report.pdf
    report/report.log
    git status 
    echo "*.log" > .gitignore
    echo "*.swp" >> .gitignore
    git status

# Working with a remote

* Open up github
* Make a repo
* Push
* Re-clone

# Working with "others"

* Some other time, or show commit logs


# Working with Branches

    git branch develop
    git checkout develop

    create a new file
    edit another file

    add new file
    commit

    add editted filee
    commit

    checkout master; show change in the working directory

    git merge --no-ff develop

    show the git log

