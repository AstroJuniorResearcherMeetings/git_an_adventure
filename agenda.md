# Agenda for JRM Jul. 22
## Using git
-----------------------------
__1)__ Clone the repository
	
	git clone https://github.com/AstroJuniorResearcherMeetings/git_an_adventure

__2)__ Set git globals

	git config --global user.name "my name"
	git config --global user.email "myemail@utah.edu"

__3)__ Open the README.md in the respository

Demo of 

* copy the template.html to new file (cp template.html beach.html)
* add the change (git add)
* commit the change (git commit -m "message")
* push the change to the repo (git push)
* everyone does a pull (git pull)

__4)__ Conflict resolution

If two people edit the same file you need to resolve the conflicts.

* PersonA edits file does a add,commit,push
* PersonB edits same file does add,commit then tries to push and will receive a git message
* PersonB does a pull
* PersonB resolves change using emacs
* PersonB does a add,commit,push

__5)__ Everyone is given a file to create and do an add,commit, push on. (optionally everyone then edits a file)

__6)__ Everyone allowed to go at making changes based on the rules in the README.md
* add files, make changes, go adventuring!


