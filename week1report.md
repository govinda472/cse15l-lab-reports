# Lab 1 tutorial:remote access

## installing VS code


step 1:  download [Visual studio code](https://code.visualstudio.com/Download)

![image](https://user-images.githubusercontent.com/75463270/211932151-b56128f7-c615-497c-b542-16b21febf58d.png)

step 2: open the downloaded Visual studio installation file and follow the instructions to install it.

![image](https://user-images.githubusercontent.com/75463270/211932262-dd645c29-e4e9-47e0-b467-a7877721536c.png)

Step 3: wait until the installation is complete

## connecting remotely

step 1: open Visual studio code and select new terminal
![image](https://user-images.githubusercontent.com/75463270/211932380-5f2b88ea-dabc-43bf-8215-062e895586a1.png)

step 2: type the following code into the terminal 
>ssh [your cse username]@ieng6.ucsd.edu

Then type your password into the terminal and press enter,it will connect you to the server remotely

![image](https://user-images.githubusercontent.com/75463270/212562108-4dedbc51-7c4e-4f02-b899-4eb6540d80f6.png)

## Trying Some Commands
try typing in some of the codes down below into your terminal and see what it does

>cd ~

>cd

>ls -lat

>ls -a

>ls <directory> where <directory> is /home/linux/ieng6/cs15lwi23/cs15lwi23abc, where the abc is one of the other group members’ username

  >cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/

 >cat /home/linux/ieng6/cs15lwi23/public/hello.txt
  
  you can visualize the effects of following codes down below
  
  ![image](https://user-images.githubusercontent.com/75463270/212562755-3732a279-206e-4815-b5c5-9d8bf4420bd4.png)

