# Lab-8_202001144

Name = Sangani Hemil Sharadbhai

Student ID = 202001144

1. Create a new Eclipse project, and within the project create a package.

![image](https://user-images.githubusercontent.com/91768278/233313987-ea3f3711-cc34-4a0d-a520-4ffebc505ef6.png)

2. Create a class for a Boa.

![image](https://user-images.githubusercontent.com/91768278/233315511-5bba7845-e03f-4ffa-a024-04f97df25205.png)

3. Create a JUnit Test Case in Eclipse

![image](https://user-images.githubusercontent.com/91768278/233316054-3a47dc72-3688-4801-86f5-af6892ee456e.png)


![image](https://user-images.githubusercontent.com/91768278/233316291-6680ba5d-94b9-4d0e-b7b3-16e06c0bf9f0.png)

4. Now it’s time to write some unit tests. Notice that the BoaTest class that JUnit created
for you contains stubs for several methods. The first stub (for the method setUp()) is
annotated with @Before. The @Before annotation denotes that the method setUp()
will be run prior to the execution of each test method. setUp() is typically used to
initialize data needed by each test. Modify the setUp() method so that it creates a
couple of Boa objects


![image](https://user-images.githubusercontent.com/91768278/233317311-2e8ec92f-e3a1-46d8-9e5d-663ab0ec7082.png)


5 JUnit also provided stubs for two test methods, each annotated with @Test. Work on
the testIsHealthy() method first. The purpose of this method is to check that the
isHealthy() method in the Boa class behaves the way it’s supposed to. In the JUnit
tutorial, read the section on “Writing Tests”. Modify the testIsHealthy() method so that
it checks the results of activating the isHealthy() method on the two Boa objects you
created in setup().
Likewise, modify the testFitsInCage() method to test the results of that method. Make
sure your test is robust; it should check the results when the cage length is less than the
length of the boa, when the cage length is equal to the length of the boa, and when the
cage length is greater than the length of the boa.

![image](https://user-images.githubusercontent.com/91768278/233318191-e68adb39-ef81-4b65-b58b-d74e931c9947.png)

6. Now you can run your tests. Read the section “Running Your Test Case” in the tutorial.
Did you get a green bar in the JUnit pane? If you got a red bar, use the output in the
JUnit pane to determine which test(s) failed. Fix your tests, and try running the test
case again.
It’s important to note that a red bar doesn’t necessarily mean that the test case is
written incorrectly; it could be that the method that’s being tested isn’t correct. In fact,
that’s what unit testing is supposed to do – help us find errors in our code. When a test
fails, you need to determine if the error is in the test case itself or in the code it’s
testing.


7. Add a new method to the Boa class, with this purpose and signature:
```

// produces the length of the Boa in inches
public int lengthInInches(){
// you need to write the body of this method
}

```
Add a new test case to the BoaTest class that tests the lengthInInches() method. Make
sure you annotate the new test method with @Test. Run your tests.

![image](https://user-images.githubusercontent.com/91768278/233321934-5ddab701-667f-4226-b732-d7056f94e326.png)

![image](https://user-images.githubusercontent.com/91768278/233322090-69de09cf-edbb-4693-ad87-0ecd9a80d406.png)


After Running new Test Case that tests the lengthInInches() method.

![image](https://user-images.githubusercontent.com/91768278/233322894-b3055ad0-5152-4938-b697-1742df114758.png)

