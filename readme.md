# Git Configuration List

```bash
    # What i configure when installing git bash
    git config --list
```

## Add new configuration

```bash
    # config new user in git
    git config  --global user.name "Abdul Mannaf"
    git config --global user.email "idbmannaf@gmail.com"
```

## How to connect multiple user in same window

```bash
    # Check Git Status
    git status
    ## if you want to inisialize git in loacal then you need to run
    git init

    # if you run ls command then you will doesn't show .git file You need to run

    #show all files include hidden files
    ls -a

    # for git track files'/ Staging Comment [if you want to add many nested file then you need to run --all]
    git add { . / FILENAME/ --all }

    #commit the tracked/Staging files

    git commit -m "This is new Commit" # [ -m For message]

    # get all comment history/ Log history
    git log # you can add --oneline then you will see comment messages only

```
