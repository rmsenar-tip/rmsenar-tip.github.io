---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


![1stpic](https://user-images.githubusercontent.com/75377706/104594832-ad7dd280-56ac-11eb-8dba-16a7f428d5d2.PNG)


## PRELIM

###   Hands-on Activity 2: Install and configure your repository in remote Git in GitHub

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

## OUTPUT

.
 HA2.md
 README.md


