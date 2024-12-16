<u>**D1 - 13.12.24 7:30pm to 9:00pm** </u>
Team meeting with Anu and the Project teams
First Anu was guiding us to register & download essential tools & account like
 Visual Studio Code, Git Account , download Git and AWS account.
Then Anu explain what is GIT and how it is works.

<u>**Learnt GIT term like**</u> :

**- Repository:**
Storage space where the project files and version history are tracked using GIT.

**- Git :**
A version of control system that track change in code and for collaborate and manage project.

**- Commit :**
is a snapshot of change made to files in GIT repository,like saving the work.

**- Pull:**
Retrives the latestchanges from a remote repository and merges with local repository.

**- Branch :**
Seperate line of development in GIT.Once the work completed, branch can be merged back.

**- Push :**
Upload local commits to a remote  repository like GitHub to allow ither to access the update.

**- GIT add:**
Add specific files or changes to the staging area , preparing for a commit.

![Git Repository Explaination](<Assets/Git repository explaination.png>)

***

Then we create our new Repository in GitHub with Lego-city (Public)
and linked the Git with new Visual Studio Code with steps below:

Open downloaded GIT software in computer and open GIT Bash.
In order to get the - Generate public/private ed25519 key pair and OPENSSH PRIVATE KEY
Key in code below:

*  $ ssh-keygen -t ed25519 -C "lee.itcloud2024@gmail.com"
* -- $ cat /c/users/abbyr/.ssh/id_ed25519
* -- $ cat /c/users/abbyr/.ssh/id_ed25519.pub ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIC4qqAJ/19lGYZ0QwXAnY7+vO9o8fDBhPIu0QFxp1h78 lee.itcloud2024@gmail.com
* $ ssh -T git@github.com

Then type Yes

![Create SSH key](<Assets/Create SSH key.png>)

Then open Github Account > Click on top right account icon > Click on Setting
On the left panel , click on SSH and GPG keys
Add SSH key with SHA256:MlQsHtE3KstGLP+yJU6dK41pPEcCTE8BLfXpQd5RCYI , Then added.

***

Then open create a new folder in Computer under name of Lee
In the Lee folder, press Shift key + rightclick mouse , select [Open GIT Bash Here]
In the GIT Bash type code below:
$ git clone https://github.com/anuvindhs/TechWithAnuvindh.git
Then will Complete clone into 'TechWithAnuvindh'

![Clone into 'TechWithAnuvindh'](<Assets/Cloning into 'TechWithAnuvindh'.png>)

Open Visual Studio Code > Open Folder > lee
Under Lee folder > create new folder 03 Lee
Under 03 Lee Folder > create a Day1.txt to create this note about what we have learnt today.