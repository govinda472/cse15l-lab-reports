# Lab Report 2 - Servers and Bugs
## part 1



my code used to run the server
![image](https://user-images.githubusercontent.com/75463270/215680447-28516e71-388a-4bb9-a095-1edf1f976fde.png)





## first use of add command


![image](https://user-images.githubusercontent.com/75463270/215680955-8d32072b-0b67-4cab-8e57-74329efa2e60.png)
  
  > the main Method that is called upon within the function in my code handleRequest is which breaks the URL down and passes it to different components withinself


> The method takes the URL in and breaks it beyond the add? point into 2 segment with "=" acting as the divider. It takes the later part of the division and appends it
> to the array list to store the item

> for instance the methods strips it into 2 components and stores it in a list size 2 the following link http://localhost:6940/add-message?s=Hello would be broken into a list as {s,Hello}
> s=<String> and  store_list(which stores the previous values)is the relevant arguement 
> from this request The arraylist labeled store_list is appended by the string "Hello"
> Consequently the output by modifies by additional line by the element that was in the URL
>for this instance it would be "Hello"
  

## second use of add command
  

  
![image](https://user-images.githubusercontent.com/75463270/215681102-dd4ea5ec-daf5-484a-aa67-5565bff03429.png)
  
  > the main Method that is called upon within the function in my code handleRequest is which breaks the URL down and passes it to different components withinself


> The method takes the URL in and breaks it beyond the add? point into 2 segment with "=" acting as the divider. It takes the later part of the division and appends it
> to the array list to store the item

> for instance the methods strips it into 2 components and stores it in a list size 2 the following link http://localhost:6940/add-message?s=How%20are%20you would be broken into a list as {s,How are you}
  
> s=<String> and  store_list(which stores the previous values)is the relevant arguement 
> from this request The arraylist labeled store_list is appended by the string "How are you", so the store_list would equal{"Hello","How are you?"}
> Consequently the output by modifies by additional line by the element that was in the URL
>for this instance it would be "How are you?"
 > the overall output would be 
  
 > hello,
  >how are you
  
  
  
# part 2
  
  

  
  
  
# part 3
  
  In a couple of sentences, describe something you learned from lab in week 2 or 3 that you didn’t know before.
  > there were alot of new concepts that I was introduced to in Lab 2 and 3 that I didn't know before. I didn't know how to host servers locally/remotely, and now I have somewhat grasped the basics of pushing files onto a remote system and running the server and accessing it through a web browser. Furthermore, I didn't know how to design code to break down the URL in my webbrowser, which I learned last week in lab 2. Moreover, I enriched my debugging knowledge in lab 3.
  
