---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


![1stpic](https://user-images.githubusercontent.com/75377706/104594832-ad7dd280-56ac-11eb-8dba-16a7f428d5d2.PNG)


# PRELIM HANDS-ON ACTIVITY


##   Hands-on Activity 2: Install and configure your repository in remote Git in GitHub

### December 13, 2020 

1. Create an account in Github

Username should be your given initials and last name followed by -tip (e.g.  ajcanlas-tip)

Use your TIP email address for this (if you have already linked your email with GitHub create a separate one)

Verify your account in your email in GitHub,


![2ndpic](https://user-images.githubusercontent.com/75377706/104602442-609ef980-56b6-11eb-8d79-6c48644c0cb0.PNG)

2. Create a repository with your username (in my case it is ajcanlas-tip) without any files, and it should be public.

![3rdpic](https://user-images.githubusercontent.com/75377706/104603935-e0799380-56b7-11eb-8ba4-d7b40d5bad48.PNG)

3. In your Alpine VM clone the repository you just created in my case this is my url (https://github.com/ajcanlas-tip/ajcanlas-tip.git (Links to an external site.))

![4thpic](https://user-images.githubusercontent.com/75377706/104604429-4ebe5600-56b8-11eb-9815-f59bf74ae475.PNG)

4. Create a profile with Markdown this is a cheat sheat (Links to an external site.) in a "README.md" file

README.md should have the following:

1. Your full name

2. Year Level

3. Interests

4. email address

5. Computer specs (CPU/Ram size/Disk type and size)

5. To add it to your profile add the README.md file commit it then push it in the repository (to push a repository use git push -u origin master)

Commands:

git add README.md

git commit -m "First commit"

git push -u origin master

![5thpic](https://user-images.githubusercontent.com/75377706/104604835-bf657280-56b8-11eb-949f-dd01e731656a.PNG)

6. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.) 

7. Clone your newly forked repository with git clone h (Links to an external site.)ttps://github.com/< your username /sysad2-12021.git and  go in the repository directory.

![6thpic](https://user-images.githubusercontent.com/75377706/104605105-0ce1df80-56b9-11eb-878b-ad39fa84bb63.PNG)

8. Make a new branch named "activity2" using git branch activity2 and git checkout activity2

![7thpic](https://user-images.githubusercontent.com/75377706/104605224-2d119e80-56b9-11eb-8715-eaf7866d0cb1.PNG)

9. Make a new new remote upstream with git

![8thpic](https://user-images.githubusercontent.com/75377706/104605544-9abdca80-56b9-11eb-941b-5b27aed284f0.PNG)

10. Create your directory with your username, create a directory named "activity2" add the previous README.md file as HA2.md

Command used:

1. mkdir <your username>

2. mkdir activity2

3. cp <path of your README.md file> HA2.md

![9thpic](https://user-images.githubusercontent.com/75377706/104605694-c93ba580-56b9-11eb-8f1a-4009f4a5b0ee.PNG)

11. add,commit and push it to your activity2 branch

Commands used:

1. git add HA2.md

2. git commit -s -n "activity2"

3. git push -u origin upstream

![10thpic](https://user-images.githubusercontent.com/75377706/104605831-f425f980-56b9-11eb-87ff-8917888f9d8a.PNG)

12.Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.) and activity2 branch of your forked repository

![11thpic](https://user-images.githubusercontent.com/75377706/104605933-14ee4f00-56ba-11eb-852a-51f0f52a902e.PNG)

# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/activity2](https://github.com/rmsenar-tip/sysad2-12021/tree/activity2)

![actvitiy2_tree](https://user-images.githubusercontent.com/75377706/104674432-9e376d00-571e-11eb-8391-d237c7acbdca.PNG)


## Hands-on Activity 3: Ansible Basics

### December 13, 2020 

Setup is Alpine and Ubuntu VMs are connected via a local network, in my case

Alpine VM, IP is 192.168.122.117 (Or Any VM that has Git installed)

Ubuntu VM,IP is 192.168.122.125 and hostname should be ubuntu-<your student number> (e.g. ubuntu-1110670)

1. Fork the instructor repository and clone the repository.

2. Create a new branch called "activity3" and checkout in that branch.

3. Create a directory with your username as its name and go inside of it, and create a directory called "activity3" and go inside it.

4. Install Ansible via apk in your Alpine VM.

5. To check if you installed Ansible correctly check the python version it in Ansible version command would reflect python 3.

6. First, create a configuration file named "ansible.cfg", Ansible checks per-directory thus you can have multiple configurations in a system depending on your configuration file in the current directory.

7. Next, populate the ansible.cfg file with basic information such as inventory, host verification, and your default remote user.

8. Next, create your first inventory file with Ubuntu IP on it.

9. Then try to connect using "ping" module via adhoc command

10. Now use "shell" module to check the user via bash commands. (check for the user, hostname, and id)

11. And we can use the "copy" module to create a file with a certain file with the content or copy from your local VM to your remote VM.

12. For more modules, you can check this link (Links to an external site.) of the module index.

13. You can also check the description of the module using ansible-doc 

14. Also, you can group your inventory via the grouping feature of Ansible.

15. Add commit push and create a PR.


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/activity3](https://github.com/rmsenar-tip/sysad2-12021/tree/activity3)

![actvitiy3_tree](https://user-images.githubusercontent.com/75377706/104675042-a80da000-571f-11eb-9e68-4e126ac0cd88.PNG)


## Hands-on Activity 4: Ansible Playbooks

### December 13, 2020 

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity4" from master branch using git branch activity4 and git checkout activity4

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity4" and go inside it.

4. Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Create a playbook that install java via package manager , and install boto,ansible,and openstack py packages using pip in both Ubuntu and Centos.

7. add,commit and push it to your activity4 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity4 branch of your forked repository.


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/activity4](https://github.com/rmsenar-tip/sysad2-12021/tree/activity4)

![actvitiy4_tree](https://user-images.githubusercontent.com/75377706/104675885-4f3f0700-5721-11eb-849f-a4ea19a3e7f9.PNG)


## Hands-on Activity 5: Implement Ansible roles in playbooks

### December 13, 2020 

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git

2. Clone your newly forked repository. 

3. Make a new branch named "activity5" from master branch using git branch activity5 and git checkout activity5

Note: To Prevent Conflicts Create a directory with your username as its name and go inside of it, and create a directory called "activity5" and go inside it.

4. Make a new new remote upstream with git remote add upstream https://github.com/ajcanlas-tip/sysad2-12021.git

5. Optimize the playbook in Hands-on Activity 4: Ansible Playbooks

7. add,commit and push it to your activity5 branch

8. Request a pull request for the master branch in https://github.com/ajcanlas-tip/sysad2-12021.git  and activity5 branch of your forked repository.

# OUTPUT
[https://github.com/rmsenar-tip/sysad2-12021/tree/activity5](https://github.com/rmsenar-tip/sysad2-12021/tree/activity5)

![actvitiy5_tree](https://user-images.githubusercontent.com/75377706/104676475-6a5e4680-5722-11eb-86ee-3e22ff1e2052.PNG)


## Quiz 2.1: Ansible

### December 13, 2020

1. Create a directory named "quiz21" in your student number directory in Quiz 1.3/
2. Create a markdown file named "README.md" in the newly created directory with the following contents:
3. How to create an Ansible Configuration.
4. How to create an Ansible Inventory.
5. How to create an Ad-hoc Ansible command with setup and shell module.
6. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.1](https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.1)

![quiz21_tree](https://user-images.githubusercontent.com/75377706/104678318-1bb2ab80-5726-11eb-8e9a-1a70058f61e0.PNG)


## Quiz 2.2. Ansible Playbooks

### December 13, 2020

Follow the procedure:

1. Create a directory named "quiz22" in your student number directory in Quiz 1.3
2. Create a markdown file named "README.md" in the newly created directory with the directory summary.
3. Transform this procedure (Links to an external site.) as a playbook 
4. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.2](https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.2)

![quiz22_tree](https://user-images.githubusercontent.com/75377706/104678870-5bc65e00-5727-11eb-956d-5f4237050cd9.PNG)


## Quiz 2.3. Ansible Roles

### December 13, 2020

1. Create a directory named "quiz23" in your student number directory in Quiz 1.3
2. Create a markdown file named "README.md" in the newly created directory with the directory summary.
3. Optimize Quiz 2.2 with roles.
4. Then create a Pull request and put your forked repo in the only question of this quiz (Note answer this quiz as well as create a pull request).


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.3](https://github.com/rmsenar-tip/sysad2-12021/tree/quiz2.3)

![quiz23_tree](https://user-images.githubusercontent.com/75377706/104679279-54538480-5728-11eb-92cf-7288168f0ba3.PNG)


## Hands-on Prelim Exam

### December 14, 2020

1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.)

2. Clone your new repository in your VM https://github.com/< your username >/sysad2-12021.git

3. Create a branch named "prelim-exam" and checkout in that branch. 

4. Create an Ansible playbook that does the following with an input of a config.yaml file

Role 1 (python):

1. Installs the latest python3 and pip3

2. use pip3 as default pip 

3. use python3 as default python 

Role 2 (Java)

1. Install Java open-jdk

Role 3 (Change motd)

1. Create Motd containing the text defined by a variable defined in config.yaml file and if there is no variable input the default motd is "Ansible Managed node by (your user name)"

Role 4 (Create user)

1. Create a user with a variable defined in config.yaml

5. push and commit your prelim-exam branch in the VM (no need for ansible.cfg and inventory upon pushing)

6. request a pull request from that branch in GitHub

7. For your prelim exam to be counted, please paste your repository link as an answer in this exam.


# OUTPUT

[https://github.com/rmsenar-tip/sysad2-12021/tree/prelim-exam](https://github.com/rmsenar-tip/sysad2-12021/tree/prelim-exam)

![prelim-exam_tree](https://user-images.githubusercontent.com/75377706/104679706-40f4e900-5729-11eb-9dc0-7aa9845ae51f.PNG)


[#Link to another page](another-page)
