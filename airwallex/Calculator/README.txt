
1. This is a maven project, and hence all dependencies are maintained by maven.
2. This project could be imported into Eclipse. Just click on File->Import Existing Maven Projects, and select the root folder.
3. To compile the project, run 'mvn compile'.
4. To run the project from eclipse, right click on Calculator->Run as->Maven Build and then proceed with inputting the expression for the stack.
5. To run the project from command line, navigate to root folder of this project, and type 'mvn exec:java'
6. To run the test case, type 'mvn test'. From Eclipse, right click on the project, Run As -> Maven Test.
7. To generate the packaged jar, type mvn package. The Calculator-0.0.1-SNAPSHOT.jar would be generated inside the target folder.

The test cases contain the 8 examples in the assignment in CalculatorTest Junit test case