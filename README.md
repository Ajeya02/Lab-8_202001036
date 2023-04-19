# IT 314 - Software Engineering 
## Lab 8 : Unit Testing with JUnit
### Student Name : M.M.Ajeya
### Student ID: 202001036
### Lab Exercises

1. I created a new Java project in eclipse with name Lab8 and created a package inside it with name mypackage
![image](https://user-images.githubusercontent.com/91492166/233043691-bf3520a0-9885-4b1f-9134-505d16769eb8.png)

2.I then created a class with name Boa and then added the given code inside it. 
![image](https://user-images.githubusercontent.com/91492166/233043729-68055248-bd5f-457a-993d-e40dd0c56a4c.png)

3.Then I created a JUnit test file for the Boa Class with name BoaTest.
![image](https://user-images.githubusercontent.com/91492166/233043793-cce10564-2185-42ed-aae1-74e42fa814dc.png)


4.Then I modified the setUp method to initialize the variables.

5.Then I also implemented tests for the given two functions testIsHealthy() and testFitsInCage(). 
![image](https://user-images.githubusercontent.com/91492166/233043898-12979e28-06f3-4afd-8e23-cce80c1bb9e7.png)
For testing thee fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given lenght is greater than,less than or equal to actual length of object.The behaviour will be similar in both cases.

6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output. 
![image](https://user-images.githubusercontent.com/91492166/233043953-d901b280-54cb-4884-b5d9-f4a872eb623d.png)
It can be seen that 2 out of 2 test cases have been passed.

7.Then I added a new method to the Boa class with name lenghtInInches() to get the length in inches. 
![image](https://user-images.githubusercontent.com/91492166/233044024-1df5123a-d661-4346-8439-4b89c607085e.png)
As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.

8.Then I wrote another test case for this new method and ran the 3 test cases together.
![image](https://user-images.githubusercontent.com/91492166/233044081-4fecb479-3b8d-4fb6-9b4b-6378bf74a53d.png)


Thus, test cases have been written for the given Boa class and all the three methods have been tested with required Junit test cases.
