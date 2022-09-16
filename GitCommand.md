# Git Tutorial
--> To check your Git Verison

```git --version ```
# Config username and user ID

--> To set user name and user email

``` git connfig --global user.name "UtkarshDubey0242" ```

``` git config --global user.email "utkarshdueby0242@gmail.com" ```

--> To check config detail 

``` git config --global user.name ```

``` git config --global user.email```

--> Alternate way to change your username and emailID

``` git config --global --edit```

--> How to make directory

```mkdir <filename> ```

--> How to change the directory

``` cd filename/ ```

--> To initialise a Git repo 

``` git init ```

--> To check list of file and hidden file 

``` ls```

``` ls -a  //to show hidden file//``` 

--> To check the git status to know the changes in your repo

``` git status ```

# Staging Area


--> To add a single file  

``` git add <filenmae> ```

--> To add all files in your project 

``` git add .```

# For Commiting 

--> To commit the added file 

``` git commit -m "Message you want to add"```

--> To track numnber of commits we have done so far

``` git log ```

--> To check your commit at any given position

``` git checkout <HashCode>```

--> To again visit your last commit

``` git checkout master```

--> To check your branch

``` git branch ```

--> How to make branch 

` git branch <branch name> `

--> To make nested branch in master

` git checkout -b utkarsh/add `

--> To mergre diffrent branch 

``` git merge anuj/add ```

--> To ignore some file which you dont want to add in your github repo 

1> first make a ignore file 

``` touch .gitignore```

2> type the name of that file which you want to ignore in .gitignore file

--> To ignore the whole folder at a time 

lets say we made some folder (secretkey), (help) and want to ignore both the file than we can just do ```secretkey/help```


# Push Repo

```git remote add origin <github repo link>```

```git remote -v```

To push master branch

```git branch -M master```

```git push -u origin master```

If you want to push other branches

```git checkout branch_name```

```git push -u origin master```

or 

```git push -u origin dev```





