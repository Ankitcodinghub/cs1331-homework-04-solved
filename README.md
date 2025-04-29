# cs1331-homework-04-solved
**TO GET THIS SOLUTION VISIT:** [CS1331 Homework 04 Solved](https://www.ankitcodinghub.com/product/cs1331-homework-04-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109894&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1331 Homework 04 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this assignment, we will be testing your understanding of class design and inheritance.

Introduction

Problem Description

The current codebase for managing the people at the Olympic event violates some of the principles of good class design, namely Single Responsibility and Open/Closed. Your job is to refactor this code base to conform to these principles. This assignment is fairly open ended, so you have freedom to create new files and name them as you like. Consequently, most of your grade on this assignment will be on your design choices, and your explanation of those design choices.

Background

Before beginning this assignment, it would be wise to familiarize yourself with the first two SOLID design principles (Single Responsibility and Open/Closed). To give you a general idea of each principle, we will summarize them briefly in this section, but don’t be afraid to branch out and do some of your own research!

Single Responsibility Principle

This principle is fairly intuitive. It basically means that each class should only really be responsible for managing and manipulating its own information, and there shouldn’t be that much information to manage. Essentially, this principle suggests the use of many smaller classes, each with a very specific purpose over the use of larger, broader classes. Doing this helps to make the code more modular, reusable, and extensible.

Open/Closed Principle

The short form of this principle would be, “Open for extension, but closed for modification.” Essentially, it means that when you write a class, you’re done. When you need new features, this means you can’t go back and add code to that class, and this is for good reason. If for every time you needed more features you just tacked them onto the same class, you would soon have a very broad class that is doing too many things. Moreover, requiring everyone on a team to edit the same file makes work a bit of a hassle. Instead, it’s better to close classes for modification, but leave them open for extension. This means that subclassing a class is OK when you need to add more features or change functionality.

Solution Description

Athlete.java

● Refactor Athlete.java to make it conform to the SOLID principles. Feel free to make additional classes and redistribute the code in Athlete.java. You should not be adding additional methods including getters/setters/constructors.

❍ Hint: pay attention to what the play method is doing, and what it is using that private instance field for. You should definitely be able to improve the implementation of this method.

❍ Hint: what are things all Athletes should be able to do? What things are specific to specific kinds of Athletes?

● Each type of Athlete should also properly override the Object equals method such that two Athletes of the same type that have the same name should be considered equal.

● In the class JavaDoc for Athlete.java, briefly explain what SOLID principle(s) the original implementation was violating and how, and also how your refactoring has solved it (answer in 2-5 sentences, so don’t write an essay please).

● Now, use your new implementation to add support for Hockey Players. Hockey Players should have some special instance field, a getter for it, and they should have some special method that prints something out (Use your imagination. We are grading more on your class design, and are not particularly concerned about your implementation of this method. It doesn’t even need to be a Hockey Player if you don’t want. It could be a StarCraft player. What a time to be alive!).

EventManager.java

● The EventManager is a really busy guy. Because of budget cuts, he’s basically running the whole show and has a ton on his plate. He’s in charge of training the Athletes, cooking for them, making sure they’re not cheating, and organizing the games. Often times he gets home late at night, and his health and married life have been suffering. He decided he needs to reevaluate where he is in life and has turned in his two week notice.

● Do you notice which of the SOLID principles has been violated by assigning so much work to the EventManager?

● Refactor EventManager to make the code conform to the SOLID principles. Feel free to create additional classes as you please. You do not need to create any additional methods for this class.

Olympics.java

● Now, create a file called Olympics.java to test your code. This file should be the main entry point for your program.

● Make an array that has one of each kind of Athlete.

● Iterate over that array, and call the play method on each Athlete.

Javadocs

You will need to write Javadoc comments and watch for checkstyle errors with your submission.

● Every class should have a class level Javadoc that includes @author &lt;GT Username&gt; and @version

&lt;version number&gt;.

● Every public method should have a Javadoc explaining what the method does and includes any of the following tags if applicable:

❍ @param &lt;parameter name&gt; &lt;brief description of parameter&gt;

❍ @return &lt;brief description of what is returned&gt;

See the CS 1331 Style Guide on Canvas for details.

Checkstyle

For each of your homework assignments we will run checkstyle and deduct one point for every checkstyle error, with the points deducted being capped.

● You can run checkstyle on your code by using the jar file found on Canvas that includes xml configuration file specifying our checks. To check the style of your code run java -jar checkstyle-6.2.2.jar *.java.

● To check your Javadocs run java -jar checkstyle-6.2.2.jar -j *.java.

● Note that the command for checking code and the command for checking Javadocs are different.

You will have to run both commands to fully test for style errors.

● Javadoc errors are the same as checkstyle errors, as in each one is worth a single point and they are counted towards the checkstyle cap.

● You will be responsible for running checkstyle on ALL of your code.

● Depending on your editor, you might be able to change some settings to make it easier to write style-compliant code. See the Customization Tips on Canvas for more information.

Collaboration

● What general strategies or algorithms you used to solve problems in the homework

● Parts of the homework specification you are unsure of and need more explanation

● Online resources that helped you find a solution

● Key course concepts and Java language features used in your solution

Examples of approved/disapproved collaboration:

OKAY: “Hey, I’m really confused on how we are supposed to implement this part of the homework. What strategies/resources did you use to solve it?”

Submission

● Submit ALL of your Java files for this homework as attachments to the Homework 4 assignment on Canvas. You can submit as many times as you want, so feel free to submit as you make substantial progress on the homework. We only grade your last submission, meaning we will ignore any previous submissions.

● If you submit multiple times Canvas will append a number to your Java file (Athlete.java becomes Athlete-1.java). Do not worry about this, we will fix the file name before compiling and running your code.

● Non-compiling code will be given a score of 0. For this reason, we recommend submitting early and then confirming that you submitted ALL of the necessary files by re-downloading your file(s) and compiling/running them.

Good Luck! (°□°)/
