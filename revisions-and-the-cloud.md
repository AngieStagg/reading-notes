# Revisions and The Cloud - Class Three

GitHub provides internet hosting for software development utilizing version control. Version control allows you to make changes to a file, but then be able to go back to before you made that change and get that previous version.  Imagine this on a grand scale with multiple users and multiple versions and you see the popularity of GitHub.  

- VCS - Version Control System
- CVCS - Centralized Version Control System
- DVCS - Distributed Version Control System

Imagine you have the ability to save and revisit different versions of a file, that would be VCS.  Now, imagine you still have that ability, but now you can share this file with others who you can collaborate with remotely, that is CVCS.  DVCS is all that plus added places where those files are saved.  This keeps them safe from loss should a server go down.  That is Git.  Git is a DVCS.

Git stores data in a file system made up of snapshots.  Each saved project version, when you commit, has Git create a snapshot.  Git is fast because most needed information is held locally.  This way you can work offline and don’t have to retrieve information from the server.  Since Git tracks every change it can detect data loss or corruption.  

To make a new repository, you can create one on GitHub.  You want to at least make a name and description, save it, and then copy the URL.  
- Go to your terminal 
- Get in the folder you want to store your repo
- Type **git clone URL*** (Paste the URL you copied in GitHub)  
- To add you type **add README.md** (or another name)
- To commit you type **get commit -m "put your message here"**  (Your message should include why you did what you did.)
- Now type **code .**  (code space dot) -This will launch you into VS Code, where you can further edit.
- Type git push origin main to send updated version to GitHub
