# Git Tutorial & Steps

***

* to clone the repository files in local folder
```
git clone <ssh>
```

* check brach status
```
git branch
```

* rename local branch
```
git branch -m <oldname> <newname>
```

* add updated files to index
```
git add .
```

* switch branch
```
git checkout <branch name>
```

* create and move to a new branch
```
git checkout -B <new branch name>
```

* set sublime text as default editor
```
git config --global core.editor subl
```

* create a .gitmessage file and keep a default template for commit messages
```
git config --global commit.template ~/.gitmessage
```

* commit with the message in COMMIT_EDITMSG file
```
git commit -F .git/COMMIT_EDITMSG
```

* check log
```
git log
```

| asd  | asd  | asdas  | asda  |asd   |
|---|---|---|---|---|
|  asda | asdasd  | asdasd  |  asdasd |  asdas |
| asdasd  | asdasd | asdasd  | asdasd  | asdasd  |
|  asdasd |  asdasd| asd  |  asdas a|  asdas |
