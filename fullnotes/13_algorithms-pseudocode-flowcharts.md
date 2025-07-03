
# Algorithm and Flowchart

## What is an Algorithm?

So let's start. What is an algorithm? An algorithm is a step-by-step process of solving a problem efficiently and systematically.

An example of a problem might be that you want to develop an e-commerce application. The step-by-step process that an algorithm would allow might be: login to this e-commerce website, once you've logged in, browse through the products, populate the shopping cart, check out, make payments, and the payment is converted. That's a step-by-step process, and that step-by-step process is captured by an algorithm.

## Importance of Algorithms

So an algorithm is important in software engineering courses because it provides that high-level view. You're not developing yet - you're at that high level trying to understand the problem statement. In this case, the e-commerce application - how would it function? How would users use it? That step-by-step process is captured by an algorithm.

## Features of an Algorithm

Features of an algorithm include that an algorithm must have an input and an output. Typically, for your e-commerce application, it could be your ATM machine you're trying to implement, and the process you find in an ATM machine. You will have to input something - you have to input your password in the case of an ATM machine. Once that password is confirmed, then you move to the homepage and you move to make withdrawals. After that, you end the session. 

An algorithm must have input and output, just like if you have your e-commerce application where you put in your password (it isn't a password, but your username and password). You have a response to that, which is the homepage, and algorithms must be finite. Algorithms must have an end point.

For your e-commerce application, again, you go in, you put your username and password. Once you're done with that, you have your homepage. Before you select products, that will populate your shopping cart automatically. From there you'll make payments. Once you make payments, you've ended the session and should be expecting your goods. So it should be finite, should have a start point and end point.

Algorithms should have a sequence of steps. That's also important. So that's a sequence - you log in, you select items/products, you go to your shopping cart, you make payments, and that session ends. So it's a sequence of steps.

Algorithms should be reusable. That algorithm that might work for an e-commerce application for selling cars should be able to use that algorithm to also solve and implement an e-commerce application maybe for selling bicycles and things like that. It should be reusable and able to solve similar problems.

That's another feature. Imagine having an e-commerce application where you sell cars - that algorithm should work here. That algorithm should also work for an e-commerce application for selling books, and for an e-commerce application for selling bicycles. So it should be able to solve similar problems.

## Algorithm Visualization

So those are the features of an algorithm. An algorithm can be visualized by means of a flowchart or code. We can visualize an algorithm using diagrams or symbols, or using statements/pseudocode.

So let's start with pseudocode. A pseudocode is an English-like way of stating an algorithm - a step-by-step process. Or it could be as a statement like "enter your password." A pseudocode is an informal and high-level compact view of an algorithm. A pseudocode does not have to follow any syntax and structure of a particular programming language like Python. You don't have to stick to structures of Python or C++. We don't need to stick to any structure or syntax. However, it requires you to know how computers work, and typically computers will take an input just like the computer, and then behind an ATM machine, they have that input. It takes that input and uses that to validate your account or to cross-check your account. So you must know how computers work - computers would typically take an input, computers would also provide output as output. You log in as input, have an output which is the landing page or homepage where you can browse products.

In e-commerce applications, computers can store values. So we must know these basic computer operations: compute output and store values. Once you know that, then clearly you can design algorithms.

## Problem Examples

Let's look at an exercise. We have this problem statement: suppose we need to multiply and add any two numbers supplied from a field experiment. So you carry out an experiment and you get these two numbers (with temperature or pressure), and your task is to add these two numbers and multiply them. So we have to add and supply pseudocode.

It's not a problem in any programming language - it's an English-like way of solving a problem. So once you have that pseudocode, then you can give that pseudocode to programmers. The pseudocode will help you understand the problem statement and the step-by-step process of breaking down that problem or solving a particular problem - that pseudocode or algorithm in general.

### Example 1: Adding and Multiplying Two Numbers

So let's see how it looks like. We have the pseudocode here. It says prompt user for number one (we could prompt the user for the first value). So it is not static - whatever pleases you. In this case you can see from the user for the first value. So the user enters six as an example, and six is saved as input in number one. So here, number one holds six - six is assigned to number one.

Now it prompts for the second value. Here, say imagine two is entered. So two, just like when you get the prompt to enter your password and then to enter your PIN, you see two is entered and two is saved in number two. So you have two here, we have two there. 

Now we'll have this line that says add number one to number two. Here we'll have six plus two, and six plus two gives us eight. So we have eight here.

The next line says number one times number two, which means six times two, and that would give 12.

At this point we can print out the sum. So the output here would be eight. And lastly, the product you have would output 12. And that's pseudocode for adding two numbers and multiplying two numbers - that's pseudocode.

For this high-level step-by-step process of solving a particular problem, then we can take this and give it to a programmer to implement in a particular language like Python or C++. So that's pseudocode.

### Example 2: Odd or Even Checker

That's how it looks for solving the problem statement of adding two numbers and multiplying two numbers. So let's carry on. We have the next problem statement: write pseudocode solution that takes an integer value and determines if it's odd or even. What makes a number odd or even? A number is odd or even as mentioned earlier.

So you might have five. We divide five by two - if there's a remainder, the remainder here is one. Then we know that five is an odd number. Conversely, if we have six, for example, and here the remainder is zero, then clearly we can conclude that six is even. This is clear.

So let's see how the algorithm looks like in this case using pseudocode. It says prompt the user to enter the integer. So here the user might enter six, and that will save input in norm. So this norm will be assigned six. The third line says check if remainder exists if you divide six by two. So here we are saying six divided by two - is there a remainder? There's no remainder because we have zero. So if we don't have a remainder, then print "it's even." This is clear - that means you skip this line and it goes to the last line because we don't have a remainder. 

The check: if remainder exists, if you divide the number by two. So we did that and we have no remainder. Six divided by two has no remainder. And for that reason it says the number is even. So what about if we had instead of having six, we have five?

Five here, five, and now five gets saved here. Five, and no - number rather. So five is there and we check if remainder exists. If you divide five by two, so let's do that. Five divided by two - oh no, there's a remainder of one. And if there is a remainder, then print "this is printed as output: The number is odd." And why is it odd? Because a remainder exists, and I hope this is clear.

So what about if we enter 10 here? Imagine there's 10, and now again 10 gets in here, and then again we divide 10 by two. So 10 divided by two - is there a remainder? No, we don't have a remainder. And for that reason it prints "the number is even." What about 12?

How would it work for you? How about 15? So run these numbers through this pseudocode, and so let's look at flowcharts.

## Flowcharts

A flowchart is a graphical representation of an algorithm. So here clearly we're going to be using symbols for flowcharts. Five figures are typically used to represent a flowchart symbols. So let's see them - these are the flowchart symbols.

The first is the oval, and that's for start and stop. So we'll see an example shortly. Arrows would be used to make connections - you want to see that flow from top to bottom, and your arrows will help you make that connection from top to bottom. You also have input and output.

So you want to collect input from the user - you would use the parallelogram for processing. Process by means of five plus two process, main subtraction, and to process or for assignments, we say that shortly.

To make decisions you'll use the diamond symbol for making a decision. Is this password correct? That's a decision. So you would use this for making decisions.

### Flowchart Example 1: Adding and Multiplying Numbers

So let's see the first problem and that's a problem. We have problem one - a flowchart. It says we need to multiply and add any two numbers supplied from a field experiment. So you conduct an experiment and periodically you have these two numbers popping up. Now the task is to write flowcharts that show how to carry out this task. You have two numbers and you need to add these two numbers and multiply them.

So that's a flowchart - again, have your oval for starting the process, have your oval for stopping the process. Clearly our algorithm is finite - start point and it ends. You have your parallelograms here for collecting inputs and your parallelograms here for outputting outputs. Then you have your rectangle for processing. This is clear there.

Also have your arrows showing the flow of execution from top to bottom. So let's start - you enter six. So it could be a prompt. Remember this is for your input - collecting input from the user. So let's say the first number entered is six. Six gets into number one and your system prompts you to enter the second value. The second value is entered here - that is number two.

Have two. We have the rectangle here for processing. In here it's going to process six plus two, which is eight. So your sum here would have eight. We also have multiplication here - we have six times two, and six times two will give you 12.

So we have 12 assigned here to product. And now it's time to print out the output. So we have your sum with output eight. You also have your product that would output 12. And we are done. Then we end and stop.

### Flowchart Example 2: Odd or Even Checker

So you see how to solve or how to create a flowchart to solve a particular problem. In this case, adding two numbers and multiplying two numbers. Hope this is clear. Let's move on to problem two.

Problem two says write pseudocode solution that takes an integer value and determines whether it is odd or even. What makes a value odd? A number is odd or even as mentioned earlier.

So let's draw the flowchart. So again here we have our oval for start. This should be "stop." We have our oval for stop. And now we have a diamond for decision.

We divide this by that - would there be a remainder? So your parallelogram will handle that. And just like we saw earlier, we have our parallelogram for input. We also have two parallelograms here for output. So let's run this. Enter a number.

So number one has got six. Let's say six is entered and inputted. And number one holds six at this point.

Now ask: number one, so six divided by two, or ask if the remainder is zero. Yes, zero - a decision.

If the remainder is zero, which is yes, you can see "yes" there, then the flow of execution moves here and your system prints "the number is even" as output and the system ends. So imagine if we had five.

So if we have five instead of six, we have five. So number one holds five. And here ask a question: Five divided by two - is the remainder zero? Clearly no. So the flow of execution will go to the right, go to the right, which is no. And for that reason your system flows this way and it prints "the number is old" and flow verification comes this way. And you stop.

So if an even number is entered, the flow solution goes this way, goes that way, goes that way and ends. On the other hand, if an odd number is entered in this case, five through execution goes this way, that way, that way, this way and then stops here. So that is how to solve that problem. Put your flowchart using this diagram.

You can then give your flowchart - it can be passed down to a program app and your programmer then implements what you written here in any language. So Python, Java, C++. And so assignment is to create pseudocode and flowchart for the problem statement below. So find the average of numbers entered by user.

And so we have numbers entered by user and the task will be to find the average using your flowchart and your pseudocode.
