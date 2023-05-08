Download Link: https://assignmentchef.com/product/solved-project10
<br>
Overview

In this assignment, you will develop your first complete class, following the techniques described in Chapter 3. You will also need to use several techniques from Chapter 4 regarding data types and arithmetic, in order to manipulate the numeric values involved.  You will also develop some tests to help ensure your class is working properly.

Details

Start a new project in Eclipse for this assignment.  In this project, you’ll develop a class called FuelMonitor in the XXXX package that models the behavior of an automobile’s fuel gauge and miles-per-gallon calculator.  A basic template of the required class file is provided to help get you started.  You should assume that the methods of your class will be called by other components within the vehicle (but external to this assignment).  Each method’s required behavior is already described by Javadoc comments in the provided source code file; these comments act as your requirements by specifying the expected behavior for each method.

You have freedom to choose the number and types of instance variables you use, the approaches to the calculations, and other such internal design considerations.  This is the most fundamental concept of encapsulation in an object-oriented system.  It doesn’t matter exactly <em>how</em> your class works, <u>as long as it works properly whenever the public accessor and mutator methods are invoked</u>.  There are many possible designs, and there is no single “right” or “best” solution that meets all of the functional expectations.

However, we’re also taking this opportunity to start to practice development in the idiomatic style of Java, so please be sure to review the <u><a href="https://canvas.vt.edu/courses/70397/pages/project-grading-rubric-80-point">project grading rubric</a></u> and follow its guidelines to maximize your score from the human review process.  Of course you may always ask for help in the forum at any time!

Note that our FuelMonitor class isn’t a complete stand-alone program.  It can’t be launched on its own, as it doesn’t include a main() method.  Further, no methods accept any user input, nor do any methods produce any user output.  This is intentional!  This class is meant to be just one small component of a much larger system.

Still, you obviously need to execute your code somehow, to ensure that it works correctly.  To do this, you’ll need to develop a second class called FuelMonitorTester (also in the XXXX package) in order to exercise your FuelMonitor class.  Your tester class does have a main() method, and will generally use System.out.println() to display both the expected and the actual results to the console, as suggested in the textbook.  A starting tester class is provided, to get you started, but you’re expected to add several more test cases to this.




Downloads

<ul>

 <li><u><a href="https://canvas.vt.edu/courses/70397/files/7224348/download?verifier=RPk0IPjLOi4aXlaB9sxNXsINiw864f0ULlE3rz2l&amp;wrap=1">java</a></u>This class file contains all the method declarations you need, along with Javadocs describing their required behaviors, but the method implementations are all just placeholders.  You will need to design and develop the method implementations, adding private instance variables as necessary.  You are encouraged to add private methods as well, wherever it can help reduce redundancies in your code.  Please ensure you don’t add, remove, or change the headers of any of the public methods.  The existing public methods represent the external interface of your class, and must be retained.  Other components of the larger system (outside of this assignment) will expect to work with your class using exactly these methods.</li>

 <li><u><a href="https://canvas.vt.edu/courses/70397/files/7167524/download?verifier=vG1CIj0baTJkjKaewRtrzAPRgaJVSpv4DxoAIzZM&amp;wrap=1">java</a></u>This class file runs some basic functional tests on a FuelMonitor object.  Be sure to read through all the comments of this file before starting the assignment, as there are many sample calculations that might help clarify some of the behavioral requirements.  You’re expected to develop additional test code in this file. <strong>Your must add enough tests to exercise each of the FuelMonitor methods at least three times</strong> (above and beyond the existing tests).</li>

 <li><u><a href="https://canvas.vt.edu/courses/70397/files/7167526/download?verifier=RzMQUHrePKI38ojFBXVGkKe8RxxOP4FRw4Sc1q7d&amp;wrap=1">txt</a></u>This is the expected output of running the above tester code (as provided) on a properly working implementation.</li>

</ul>




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/771.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/771.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>SAMPLE Model

<img decoding="async" width="722" height="463" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/419.png?resize=722%2C463&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/419.png?resize=722%2C463&amp;ssl=1" width="722" height="463" data-recalc-dims="1">

 </noscript>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/801.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/801.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>







<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/669.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/06/669.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Assignment need to focus on the following points

<h2><strong>Required behavior (10 points)</strong></h2>

Each program assignment will describe specific goals that your solution is to achieve. Your submission will be rated on the Excellent-to-Not-acceptable scale based on how well it achieves the assignment-specific goals described in each assignment. An ideal solution meets all of the following criteria:

<ul>

 <li>It is evident that all the functionality required by the specification is available.</li>

 <li>It is easy to see which methods and which classes will perform which actions.</li>

 <li>There are no questions about how all the pieces of your solution works together. Instead, interdependencies are clearly explained and readily determined.</li>

 <li>It is clear from your design and the approach you have taken that all of the pieces work correctly to achieve the solution.</li>

</ul>

<h2><strong>Design (10 points)</strong></h2>

Your design should be clear, easy-to-understand by other programmers, and reasonable in the context of the problem. The design score is affected by both class design and method design considerations.

<h3>Class design</h3>

The general design of your solution must be clear and reasonable. It should make good use of classes and be implemented in a sensible, understandable way. Each class you write should be clear, easy to understand, and well-designed. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>Each class conforms to a single clear abstraction.</li>

 <li>All the methods in the class relate to and are meaningful for the single abstraction.</li>

 <li>Each class’ responsibilities are clearly defined and have minimal overlap (ideally, none).</li>

 <li>Fields are properly encapsulated: everything that should be private is private.</li>

 <li>An appropriate set of accessors and mutators is provided.</li>

 <li>No class incorrectly combines multiple abstractions.</li>

</ul>

<h3>Method design</h3>

Within each class, the collection of constructors and methods you write should also be clear, easy to understand, and well-designed. Methods that you write should use algorithms that are appropriate for the task and be implemented in a sensible, understandable way. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>Each method does one thing well. Methods do not overlap in behavior.</li>

 <li>Each method has a clear, explainable abstraction that is directly related to the class in which it lives.</li>

 <li>Information is passed into methods as parameters when appropriate. There is a clear distinction between information that is stored in fields versus passed via parameters.</li>

 <li>Each public method is designed for client use, not internal use, and focuses on a self-contained task.</li>

 <li>Methods are not too long, rarely over 25 lines (half a page).</li>

 <li>Internal (helper) methods are used appropriately when necessary.</li>

</ul>

<h2><strong>Test case design (10 points)</strong></h2>

The tests that you write demonstrate the degree to which your solution meets the expected behavior in the assignment–that is, they are your best evidence that the solution does what is required. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>At least one test class per regular class.</li>

 <li>Each test class uses an appropriate test fixture.</li>

 <li>Distinct test fixtures used in multiple test case methods are placed in separate test classes.</li>

 <li>Each test method <strong>tests one thing only</strong>–that is, tests a single object state.</li>

 <li>Each test method provides a comprehensive set of assertions about the object state it is testing.</li>

 <li>Tests for relevant boundary conditions are included (not just the “average case” conditions).</li>

</ul>

<h2><strong>Readability (10 points)</strong></h2>

Your solution should be easy to read and to understand for other people. Remember that writing program code is not just about communicating with a computer–writing to communicate with other people is always a major concern. The readability of your solution will be evaluated using three separate criteria.

<h3>Commenting</h3>

One important aspect of readability is the comments that you write in your source code. Comments should make it easy for someone else to tell how and why your code works. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>Comments and Javadoc are informative, well-written, and add value–they do not simply restate the obvious.</li>

 <li>Comments follow the class <strong><a href="https://canvas.vt.edu/courses/70397/pages/commenting-guidelines">commenting guidelines</a></strong>.</li>

 <li>Comments are written to be quickly scanned, rather than requiring a detailed reading effort.</li>

 <li>Correct spelling and grammar are used.</li>

</ul>

<h3>Layout</h3>

While comments convey information, the visual layout of your source code is important for conveying structure and organization. Your layout should clearly convey this information. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>The visual layout and organization of the source code is clean, consistent, and easy to follow.</li>

 <li>Your code is easy to navigate, skim, and find exactly what you are looking for.</li>

 <li>White space and “dividers” (comments designed to provide a visual break in the flow) are used to break a file into visual “chunks” that are semantically meaningful.</li>

</ul>

<h3>Naming</h3>

Choice of names for your programming entities is a critical aspect of improving readability and documentation. This includes, but is not limited to, achieving the following goals:

<ul>

 <li>The naming conventions for the course are used everywhere.</li>

 <li>Names are meaningful, giving a clear indication of the role that is played by the corresponding entity.</li>

 <li>Classes, interfaces, and other user-defined types are named using nouns or nouns phrases.</li>

 <li>Methods are named using verbs or verb phrases.</li>

 <li>Simple accessors and mutators are named using “get”/”set” as appropriate.</li>

 <li>Predicate methods (that return boolean results) are named as appropriate questions (e.g., “isEven()”, “hasChildren()”, etc.)</li>

 <li>Correct spelling is used.</li>

 <li>Classes and interfaces are given names with an initial capital letter, while methods, parameters, fields, and variables are given names with an initial lower-case letter.</li>

 <li>Multi-word names are written using “camel case” rather than underscores: “ProductOrder” (as a class name) or “itemCount” (as a variable) or “sortByHeight()” (as a method).</li>

 <li>Constants (final static fields or Enum constants) use all-upper-case names. Multi-word constant names use underscores: “MAXIMUM_POSSIBLE_ITEMS”.</li>

</ul>

<h2><strong>Automated style checks (10 points)</strong></h2>

Web-CAT performs a number of style checks on your code automatically to ensure your code conforms to the coding standards expected in this course. This portion of your grade comes from that analysis. Be sure to fix all errors so that you get the maximum points for this criterion. If there is a particular rule you disagree with, post about it on the class discussion forum or ask in class.

<h2><strong>Correctness/testing (30 points)</strong></h2>

Web-CAT assesses your program code for this criterion, using the tests that you write and cross-checking against other tests provided by the instructor.


