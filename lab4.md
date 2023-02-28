# Lab 4
## step 4:
I typed in
> ssh cs15lwi23aci@ieng6.ucsd.edu

output:
![image](https://user-images.githubusercontent.com/75463270/221771032-e8985e29-8502-4775-89d5-2fdaf8e94525.png)


## step 5: Clone your fork of the repository from your Github account
> git clone https://github.com/govinda472/lab7.git
> cd lab7/

> I typed (tab) to auto complete the file dicrectory
  
output:
![image](https://user-images.githubusercontent.com/75463270/221772725-81fbf042-c5c9-4226-b11a-cafc41b42784.png)
  
 ## step 6: Run the tests, demonstrating that they fail
  
 > javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
 > java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples
  
>I typed (uparrow)(enter) to extract the previous line  
>I typed (tab) to auto complete the file dicrectory
  
  ![image](https://user-images.githubusercontent.com/75463270/221780401-48347e1c-e04e-4396-8807-012eb3fe1ef8.png)

  
  
  ## step 7 Edit the code file to fix the failing test
  
  >nano ListExamples.java
  
  >I edited the code by going down with (down arrow) and (right arrow)
  
  >I typed (tab)(tab) to auto complete the file name
  
  output:
  
  ![image](https://user-images.githubusercontent.com/75463270/221777753-ecaa4579-3fca-489a-92e1-1d701a708dee.png)
  
  ![image](https://user-images.githubusercontent.com/75463270/221777537-48a51419-3068-440d-a6d7-e45ee98ce9f7.png)
  
  
  ## step 8: Run the tests, demonstrating that they now succeed
  
 >javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java                       
 >java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples
  
  > I typed (upArrow) a few times to quickly access my old code that I used to run the test
  
  ![image](https://user-images.githubusercontent.com/75463270/221779254-69d582d5-f246-46ad-b578-b32529c069aa.png)
  
  
  ## step 9: Commit and push the resulting change to your Github account

    >git .add
    >git push
     >git commit "final test"

