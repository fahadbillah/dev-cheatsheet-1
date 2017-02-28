# Git Tutorial & Steps

***

* to clone the repository files in local folder
'''
	git clone <ssh>
'''
* check brach status
''' 
	git branch
'''
* add updated files to index
''' 
	git add .
'''
* create and move to a new branch
''' 
	git checkout -B <new branch name>
'''
* set sublime text as default editor
''' 
	git config --global core.editor subl
'''
* create a .gitmessage file and keep a default template for commit messages
''' 
	git config --global commit.template ~/.gitmessage
'''
* commit with the message in COMMIT_EDITMSG file
''' 
	git commit -F .git/COMMIT_EDITMSG
'''
* check log
''' 
	git log
'''
