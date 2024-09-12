# Lab 1

1: Download the given files
2: Make sure the hierachy of your folders are in order and upload the files to their respective places.
3: Then in the codespace you need to change the the directory to be in said folder.
4: Run this command to compile all .java files in your c folder: javac -d out src/c/*.java
5: Make sure to compile before running the file using the command:
javac -d out -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar src/u/HybridTest.java
6: In order to run HybridTest.java you need to run this command: 
java -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore HybridTest
