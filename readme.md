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

## Some Comment

```bash
    # Check Git Status
    git status
            #____ Git er status check korar jonno

    git init
            #____ Git inisialize korar jonno

    ls -a
            #____ hidden file soho file dekhar jonno

    # for git track files'/ Staging Comment [if you want to add many nested file then you need to run --all]

    git add { . / FILENAME/ --all }
            #____  git track korar jonno
            #____ . diye all files add korar jonno
            #____ FILENAME diye ekti file add korar jonno
            #____ --all diye sob file add korar jonno



    git commit -m "This is new Commit"
             #____  commit the tracked/Staging files
             #____  Commit korar jonno/ file ke track korar jonno
             #____  -m For message

    git log

            #____ you can use parame like --oneline
            #____ Commit history check korar jonno
            #____ --oneline babohar korle sudhu commit id and commit name dekha jay




    # how to revart commit history
    git status
    git reset --hard 0a7421d
            #____ you can use parame like --hard, --soft, etc. last is commit id and must type it
            #____ commit revart korar jonno
            #____ vul e commit hoye gele ager commit e ferot jawar jonno
            #____ Change HEAD


    git reflog
            #____ jodi ami vul e back commit or next commit e HEAD kor then abar jekono commit e fire jawar jonno commit id dorkar . ekhane all commit it dekhte pabe
            #____ jodi ei comment run kori tahole amra HEAD{0} for latest and continue

    git rm
            #____ PARAM: filename like git rm help.txt
            #____ kono ekta file jeta git track korchilo seit file take amra tracking theke remove korte pari and amara file ke delete korte pari jodi working directory theke file ta kaj e na lage
            #____ file permanently  remove korar jonno "git addd and git commit" korte hobe



```

## Branch

```bash
    git status
            #____ Git er status check korar jonno


```
