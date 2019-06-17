# DDM

This is how you do it:

1) Fork the directory
2) Download it and edit it
3) Open Git Bash and go to the folder with your edits 
i) git add .
ii) git commit -m (message you want associated with file)
iii) git push

4) Make a pull request

# One and done (setup)
### cloning a branch's repo locally. do this once into an *empty* folder.
```
$ git clone <github url to repository>
```
### tell git who you are. Should do just once.
```
$ git config --global user.name "<username>"
$ git config --global user.email "<email>"
```
# Going to work on something? (session start)
### update your local repository before doing ANYTHING during a coding session. Makes sure you are working on up-to-date files for your branch.
Navigate to your local repository/branch using cd command in git bash window, then:
```
$ git pull 
```
Now you are good to work on some code. When you're done, save locally and then do the following to update github:

### stage repository, commit changes (with comments), and then push to github
```
$ git add .
$ git commit -m 'Insert comments here'
$ git push 
```
Commits are just changes you've made to the code. github keeps track of all commits (changes). 
*always include short comments for commits!*
"Pushing to github" is just sending your updated code to github. Commit, comment, and push often! 

