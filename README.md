# Homework_1

Completed upto level 18 in Bandit wargames according to the instruction given in following site. 
The screenshots illustrate the commands used to discover the password.

[OverTheWire website][1]
[1]: http://overthewire.org/wargames/bandit/

bandit0

Level Goal:

Connect to the OverTheWire game server using SSH using provided credentials and discover password for Level 1. hostname: bandit.labs.overthewire.org username: bandit0 password: bandit0

How To:

Use an SSH application and SSH to bandit0@bandit.labs.overthewire.org. Given that the file is in the home directory, use lscommand to list the content of the directory.Notice the file named readme, and simply read this filename to find the password for the next level using the command cat readme.

Terminate the SSH session by typing exit and reconnect to the bandit game using thenew username and password for level 1.

![level1](https://cloud.githubusercontent.com/assets/18345099/14379173/67da2e8c-fd96-11e5-9095-f0c0db240e52.PNG)

bandit1

Level Goal:

Discover password for the next level stored in a file called - located in the home directory.

How To:

Login as bandit1 using the password recovered from level0 and land in the home directory. Given that the file is in the home directory named -, the command cat ./- produces the intended result. The period denotes the current working directory which in this case can be substituted with /home/bandit1.

![level2](https://cloud.githubusercontent.com/assets/18345099/14379172/67d9d360-fd96-11e5-99f1-78743bb4a49c.PNG)

bandit2

Level Goal:

Discover password for the next level stored in a file called "spaces in this filename" located in the home directory.

How To:

Given that the file is in the home directory named again the command cat should produce results. The file can is read using the command cat spaces\ in\ this\ filename in which the backslash preserves the space following it or simply type cat sp and hit Tab for the shell to fill the rest.
Terminate the SSH session and login to next level.

![level3](https://cloud.githubusercontent.com/assets/18345099/14379174/67f8ba78-fd96-11e5-8851-da5313161e4a.PNG)

bandit3

Level Goal:

Discover password for the next level stored in a hidden file in a directory named "inhere".

How To:

Try to list all what inhere directory holds with the ls command and it would show it as blank. Go through the manual of for ls command by typing in man ls and notice the argument -a used to list all items. Press q and exit. Then use the command with the argument to list literally all items. This should show three things listed. A period, two periods and .hidden. The period denotes the current directory, two periods references the parent directory and .hidden is the hidden file containing the password for the next level.
Read the file using cat /inhere/.hidden from the home directory to recover the password.
Terminate the SSH session and login to next level.


![level4](https://cloud.githubusercontent.com/assets/18345099/14379176/67fc604c-fd96-11e5-8e67-21fe39f62d47.PNG)

bandit4

Level Goal:

Discover password for the next level stored in the only human-readable file in the directory named "inhere".

How To:

List all the items in the folder and notice the file names beginning with a dash meaning that we should adjust the command. Given that there is only one human-readable file in the directory, using wildcard type in the command file ./* to identify the file with ASCII characters. This should show the only human-readable file as -file07.
Read the password, terminate the SSH session and login to next level.

![level5](https://cloud.githubusercontent.com/assets/18345099/14379177/68082f6c-fd96-11e5-8a43-fc26fda8ea95.PNG)

bandit5

![level6](https://cloud.githubusercontent.com/assets/18345099/14379179/6831b74c-fd96-11e5-9b57-977792d46c57.PNG)

bandit6

![level7](https://cloud.githubusercontent.com/assets/18345099/14379178/6830fee2-fd96-11e5-91d8-5951db1db1b7.PNG)

bandit7

![level8](https://cloud.githubusercontent.com/assets/18345099/14379182/68333cfc-fd96-11e5-8fc4-0f2d56b51d30.PNG)

bandit8

![level9](https://cloud.githubusercontent.com/assets/18345099/14379181/68323082-fd96-11e5-9d0d-0e3c5277449c.PNG)

bandit9

![level10](https://cloud.githubusercontent.com/assets/18345099/14379180/68320cba-fd96-11e5-9260-7aff9cfdb75a.PNG)

bandit10

![level11](https://cloud.githubusercontent.com/assets/18345099/14379183/68380606-fd96-11e5-820f-58267e85b99d.PNG)

bandit11

![level12](https://cloud.githubusercontent.com/assets/18345099/14379184/685ae022-fd96-11e5-8c8c-09b81d501e9d.PNG)

bandit12

![level13](https://cloud.githubusercontent.com/assets/18345099/14379186/685fcf56-fd96-11e5-997a-a7237a5c210a.PNG)

bandit13

![level13 1](https://cloud.githubusercontent.com/assets/18345099/14379185/685b552a-fd96-11e5-92f3-b7a3d4167969.jpg)
![bandit13-2](https://cloud.githubusercontent.com/assets/18345099/14379170/67d93ee6-fd96-11e5-8750-75110839fd44.jpg)

bandit14

![level14](https://cloud.githubusercontent.com/assets/18345099/14379187/6860ca8c-fd96-11e5-9689-2382e3bd0b6d.PNG)
![level15](https://cloud.githubusercontent.com/assets/18345099/14379188/6867f546-fd96-11e5-9fbc-7695a9a8c71b.PNG)

bandit15

![level16](https://cloud.githubusercontent.com/assets/18345099/14379189/686c49de-fd96-11e5-865f-29ba3ccc7b38.PNG)

bandit16

![level17](https://cloud.githubusercontent.com/assets/18345099/14379190/68971a42-fd96-11e5-97fc-765808176342.PNG)
![16-17_1](https://cloud.githubusercontent.com/assets/18345099/14379168/67ca6a7e-fd96-11e5-8bf1-7fabc94344a2.PNG)
![16-17_2](https://cloud.githubusercontent.com/assets/18345099/14379169/67d4a2fa-fd96-11e5-87c5-47714580caf6.PNG)

bandit17

![17-18](https://cloud.githubusercontent.com/assets/18345099/14379171/67d976f4-fd96-11e5-8d6d-609075b6fb35.PNG)
