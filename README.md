Download Link: https://assignmentchef.com/product/solved-ece-325-assignment-4-static-code-analysis-and-unit-testing
<br>
<table width="661">

 <tbody>

  <tr>

   <td width="661">Part 1: Static Code AnalysisConsider the CodingHorror program, although it compiles, it fails to do what the programmer wants. The programmer intends to read a string from the user, substitute all “e” characters with “o” characters, then check whether the substitution results in the string “pool”. This will never be the case, no matter what input we provide, because of faults in the code.Your task is to utilize the static analysis tool FindBugs, a popular open source static code checker for Java, to find the FIVE bugs reported by the tool and contained within the code.Hint: Sometimes one bug hides another bug; and the second bug is only revealed by removing the first bug. That is, think iteration.Note 1: Findbugs is likely to report a sixth error, Internationalization. It is something that goes beyond the scope of previous Java classes so we will ignore this one.Note 2: If you choose Firebugs version 3.0.0 or earlier (now the newest version is 3.0.1, as of Sept.30, 2018), you can only get four bugs detected.Compile theCodingHorror.javasource code into bytecodes file, and then start up the FindBugs program to analyze it: New Project &gt; Classpath for analysis &gt; Add &gt; Analyze. The application will then produce a list of bugs that are present within your code.</td>

  </tr>

 </tbody>

</table>

Your task is to provide a brief summary of each bug identified:

1.What is the bug;

2.Why it is happening;

3.Provide a solution to fix the bug.

<h1>Part 2: Unit Testing</h1>

In this part, you will explore Unit Testing (UT) by using the technique in conjunction with the Eclipse IDE to develop a trivial application. This unit test will provide 4 test suites (Question 1 to 4), which will be used to drive the development of the Calculator class.

Your task is to complete the 5 following checkpoints and submitting your final answers as a Java project.

<h2>1. Implement functionality defined by Test Suite “Question 1”</h2>

Navigate to Test Suites &gt; Question1.java, and run it as JUnit Test. An output will come up and inform you that there are errors! This is to be expected, don’t panic! Now you need to fix these errors.

Your task in this step is to fix the errors and implement only the required functionality (src &gt; Calculator.jav and re-run the Question 1 test suite.

CHECKPOINT 1: Test Suite “Question 1” runs without any problems, but other test suites fail.

<h2>2. Implement functionality defined by Test Suite “Question 2”</h2>

Navigate toTest Suites &gt; Question2.java, and run it as JUnit Test. Your task here is to fix the errors and implement only the required functionality and re-run the Question 2 test suite.

CHECKPOINT 2: Test Suite “Question 2” runs without any problems, but higher test suites fail.

<h2>3. Implement functionality defined by Test Suite “Question 3”</h2>

Navigate toTest Suites &gt; Question3.java, and run it as JUnit Test. Fix the errors and implement only the required functionality and re-run the Question 3 test suite.

CHECKPOINT 3: Test Suite “Question 3” runs without any problems, but higher test suites fail.

<h2>4. Create Test Cases within “SqureRootTests.java”</h2>

Navigate to Test Suites &gt; Question4.java, and run it as JUnit Test. Question 4 will run with no

problems because there are no test cases defined inSquareRootTests.java. So open Test Cases &gt;