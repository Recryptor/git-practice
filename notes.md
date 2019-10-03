The very first time you use a new computer
-------------------------------------------

    git config --global user.name "Dashel Bradshaw"
    git config --global user.email "Bradshawdc@s.dcsdk12.org"

Setting up a new project (Repository(Repo))
-------------------------------------------

    git init

When you want to check which step you are on
--------------------------------------------

    git status

Three step commit process
-------------------------

* Make changes to my code, (Usually working) get it completely working
* Add any changed files to the stage
    git add filename.rb
* Commit the staged files
    git commit -m "Descriptive commit message to myself and others"