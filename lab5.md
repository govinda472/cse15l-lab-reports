# Lab Report 5

## week 2 LAB

In this lab, my Lab partner and I created a web server using URl interface in java

## Step 1:


We start by downloading the latest Java JDK version from the Oracle link if we do not have it installed already. 
After downloading the Java JDK, we install it on our specific device  Windows.

## Step 2:
my Lab partner cloned the repository for the lab reports using Github Desktop,which is one of several ways to get the code from the repository.
To do this, we log in to our Github account, click on the repository page, select the <> Code button, and choose Open with Github Desktop.
then select our repository. Once the repository is cloned, we open it in Visual Studio Code.


> git clone https://github.com/ucsd-cse15l-f22/wavelet
 

## Step 3:
We read through the file NumberServer.java 
We broke down each segment of the code and figured out what it did and how it broke down the URL

We concluded that the interface called URLHandler, which takes a URL as input and responds with the text of a web page. 
We are also provided with a class called Server that starts up the server that listens for incoming connections. 
The Server class takes in the URLHandler interface and a port number as input.


# step4:
We modified the 
To build and run the server, we use two commands: 
>javac Server.java NumberServer.java  

which compiled the Java file

>java NumberServer 4000. 

which ran the java file

java command starts the server on port 4000. 
Once the server starts, we visited http://localhost:4000 in a browser on our computer to see the web page and ran the following commands on our webrowser
to check the functionality of out NumberServer

![image](https://user-images.githubusercontent.com/75463270/224604278-87ff8058-d761-4867-97c6-4f30632dfcb6.png)




# step5:

we ran the server remotely by logging into our server account 

> ssh Shurya@ieng6.ucsd.edu

after typing that command in, my partner typed his password in and pressed the key enter, which logged us on the remote server

then we cloned the server files in wavelet from github by using following command
> git clone https://github.com/ucsd-cse15l-f22/wavelet

Then we typed the following commands in to execute them

>javac Server.java NumberServer.java  

which compiled the Java file

>java NumberServer 11222. 

which ran the java file at port 11222, we choose that number since it was very unlikely someone else was using it 
so we won't have any issues running it as it won't clash with other ports

![image](https://user-images.githubusercontent.com/75463270/224604184-1e030262-5619-4c9f-99c8-53799da09ec5.png)

# step 6
we logged out of the server and open vs editor for the local
NumberServer.java 
we modified the java file for Number server to create array and add elements to it, and if s? was typed into the url
it would be broken up after = 
for instance:
> s?=cool

would have they string cool stripped from it
then would search through the array list looking for it

When searching, the list of the found words containing the query should be refreshed every time a new url is entered, 
because otherwise, the list of found words would conflict with other people’s searches.

Our code performed the correct behaviour of the requirements of the search engine

