![clone-to-system](1.jpg)
- I cloned the github repository inside of github desktop 
![clone-to-system](2.jpg)
- These are me making changes to my project folder of readme
![clone-to-system](3.jpg)
- If you press the dots on top of this screen shot you can push, pull, and commit by using the checkmark.
![clone-to-system](7.jpg)
- This screenshot contains my local user with my private key and generated public and private key to give to my aws instance. To create my public and private keys I ran the command ssh -keygen -t ed25519 -C public1. 
![clone-to-system](8.jpg)
- The screenshot above has my user git2 from my aws instance I created this by using command sudo adduser. Once I created that I had to make a directory called gaddis13 and run the command git init --bare proj1.git to create an empty repository. Using my public key I had access config in my git2 user and give it my public key file contents for my user to access and clone the repository. 
- Clone - Git command copies a repository to your local server and creates remote-tracking branches for each branch in the cloned repository. 

- init - Creates a new Git repository It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. 

- add - The git add command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.

- commit -  a commit is an operation which sends the latest changes of the source code to the repository. 

- push - The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.

