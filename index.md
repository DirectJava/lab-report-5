Shown here is Scenario 1 from Week 9 Lab.

Here is the student's comment for EdStem:

![image](https://github.com/DirectJava/lab-report-5/assets/122843554/b6730b1c-dda4-4cf7-91bc-a8f40a2b2bc9)

This is the photo of the error being taken:

![image](https://github.com/DirectJava/lab-report-5/assets/122843554/5a6a0f13-194a-42dd-be6c-57a9f6cff8e7)

TA Question: Hi, your code works fine, but do you know what did you put in at the end of the `java` line? Try deleting `.java` at the end and run it.

Here's the image of the student's correct input at the end of the `java` line:

![image](https://github.com/DirectJava/lab-report-5/assets/122843554/47700e7b-69a0-4995-8ad7-f41a8e897e97)

The bug here is one of the command lines accidentally recalled the name of the file instead of the actual contents of the file itself.

Info Setup:

1. Directory: `cd lab3` and then `ls again`. File Name: `ArrayTests.java`

2. Contents `lab3`: `FileExample.java`, `LectureExamples.java`, `LinkedListExample.java`, `ListExamples.java`, `MethodsTests.java`, and `lib`

  Contents of `lib`: `hamcrest-core-1.3.jar` and `junit-4.13.2.jar`
  
3. Commands needed:

  - `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java  
      
  - `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests.java`

4. Bug Fix: Removing the `.java` at the end of the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests.java`

Reflection:


What I learned from the lab experience in the second half of the quarter is that I also have the ability to change the contents of the file using `vim`. Inside `vim`, I can use the `h`, `j`, `k`, `l` keys to move around the `vim`. When editing, I just type `vim` and type in any letter to go into insert mode that allows me to edit stuff.
