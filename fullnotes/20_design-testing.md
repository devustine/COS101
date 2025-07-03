# Software Development: Design, Implementation, Testing and Deployment

## Overview of Essential Phases

The essential phases of the software development process include design. Once you've done your design, it could be in the form of use cases, and it could be in the form of class diagrams. It could also be in the form of pseudocode too. Once you're done with that design, you would have to move beyond that phase to implementation.

Your implementation phase involves beginning to develop your software in a preferred language. It could be Python, it could be Java, it could be C#, and it could be a mix as well.

Once you're done, you begin to do some testing and unit testing. Once you're done with that, then you deploy in your client's environment, or you might also deploy on the cloud. You rent your infrastructure on the cloud, and then you deploy your software there.

## Design Phase

Let's examine this in detail. We'll start with the design phase. This stage involves coming up with system models, also identifying system boundary.

### Use Cases

Using the use case, we'll see that shortly. This involves identifying system boundary, identifying actors and the actors that would use the system. In this case, it could be your users and you could also be backend users too. These will be your actors and also identifying the system boundary, what the system would do. Your use case would naturally capture that.

These modules are useful as they help developers understand how they're very important. How to carry out implementation - your design phase is really important. You come up with a design. It could be your class diagram, it could be your pseudocode or flow chart that will give you a sense of how you would carry out your implementation.

### System Models and Diagrams

System models such as class diagrams, sequence diagrams, and activity models are part of the design stage. Sequence diagrams show interactions between system models. Imagine you have functions - you've created functions. Two or three functions, and a sequence diagram would show that interaction between functions or models.

### Use Case Example - E-commerce Application

This is a typical example of a use case. Imagine we want to develop a solution - an e-commerce application that would allow users. This could be a client or a user. In this case, this is a user.

This could also be backend - a person from the backend. Maybe this guy can also populate items from the back end to your application. Users can come here and users can browse and view the catalog. They can look at items that you have. They can also register and register themselves to using it.

You can also order goods. Once you are done browsing, you can order goods and other things in that space. You can see these use cases are capturing our system boundary. These are the things our system will do.

Your use case would capture the system boundary, and the use case would also identify actors. In this case, we've been able to identify a user and we also have the admin. This is just an example.

### Sequence Diagrams

A use case captures system boundary and also identifies actors. The earlier diagram, which is the use case, now captured system boundaries and actors.

Now look at the relationship between functions. Imagine this is our user. Our user would typically browse the catalog. Imagine you had a function, maybe you click a function, and that will now review a particular page where housing different items. Once you're done browsing, you can see that's a function or you can see a company.

That's a function. Remember we discussed functions at some point. These are another function or components. The user would typically interface with this catalog and once it will have a response, you have a catalog displayed.

Once you're done with that, you order your goods. You do some ordering. Once you're done, the function also returns to the sacred world. These are your order goods. You could also have other functions here too.

Could also have other functions. Maybe this could be payments. You know, you would also make payments. Once the payment is completed, then you have a response to that. Typically your sequence diagram would give you that interaction between functions.

You have your user interacting with the function. You also have the feedback from that function. You could also have user interacting with another function in this case, the payment function. You can also see the feedback too. These are the functions you've been able to identify.

### Implementation Details

How do we now do this implementation? We identify that we're going to be using this function, we're going to be using other functions. How do we now implement these functions?

Your class diagram would give you that opportunity to look in detail how to implement functions. Imagine looking at your order function. You can see this is a class diagram. Within a class, you would typically have functions. Imagine we have this order, and within this order class, you will have different functions embedded.

You can see calculate subtotal, calculate tax, calculate total, and calculate weight. We also have different functions within a particular class. Earlier with the sequence diagram, it would help you highlight relationships between the actor and functions identified. While your class diagram will also give you details as to how you carry out a function implementation.

You can see this is a customer, and within that customer class, a class would typically embed functions. Functions that perform relatively the same task. We can see a customer can do some authorization and can also make payments.

You can see that as a payment class. These are typically variables. Remember we mentioned variables that your function or your classes would work with. These are variables. That's a variable within the class.

Within that class you have functions that we can call. These are functions that typically would call to perform some task. These are what these are variables. Quality variables. We have tax data. That's a variable.

Tax status is a variable of type string. Customer name is a variable. Bank ID is also a variable. These are variables. Within that class, that's a class will have functions. Here we have just one function.

I don't want to go into details when it comes to classes, but your understanding should be that class diagram houses variables that it will work with. Within that class diagram, there are collections of functions that would help us perform different tasks. As you can see here, we have calculate subtotal, we have calculate tasks that has a function that will help you calculate tasks. We also have a function that will help you do the total. We also have a function that will weigh, calculate the total weight of the items you bought.

Once you are done with the class diagram, the next task will be to now create that logic using your C code, your C code or your flowchart. So with your class diagram, along with your flow chart, that will give you a sense of how you would carry out your implementation.

## Design Considerations

Design involves building intricate design for all required modules. At this point, you would also have considerations for:

### Database Design
If you are storing data persistently into a storage facility, then clearly it makes sense to also come up with your database. How will you store your database? How will your software connect to that database? Will your database be hosted in your client environment or will your database be hosted on the cloud? These are things you would have to figure out at design stage.

### User Interface Design
We would also have to talk about your user interfaces. What kind of user interface would you prefer? Would you want a blue background, something that reflects your identity? Would you want a yellow background, something that resonates with you? These are things we would have to look at. Maybe a combination of colors too and what other things too.

### Legacy System Integration
Here too, imagine you have a legacy system, how do you now connect to that system? These are things we'll also discuss at a design stage.

### Performance, Scalability, and Security
You'll also look at performance. You would look at scalability or securities too. Are your systems secured? What will be communicating with your legacy systems? Are you using a protocol that would help you protect your data? We also look at usability. These are things you would have to consider - usability factors that can be taken into account when making design decisions.

So performance - will you be hosting your solution in a local environment such that your users can clearly reach that system instead of pushing it to the internet? Imagine if there's internet downtime, how will you connect? These are things you would have to figure out at the design stage.

## Implementation Phase

Once we've done design, created your use cases, identified the actors, and your use case has also given you that system boundary, the next will be to come up with how functions will interact - your sequence diagram. You can also have your class diagram to highlight features, variables that will play out in your implementation, and also highlighting functions within that class. Functions that will also play out within your implementation.

You can also take that further to also create flow charts and sequence diagrams. With all of this design, clearly you can begin to do some implementation. Once the design is completed, the implementation starts. This will kickstart implementation means coding using a particular language.

### Programming Language Selection
Here you can decide to use Python. You can decide to use C#. You could decide to use C or C++. You can also maybe have combinations of languages.

Imagine maybe for your backend you're using C++ because of performance, but we'll discuss this at some point. Because of performance, and maybe you're using Python tool to maybe do some connections or to do the user interface.

If they request, Python would reach out to C++ to do those heavy tasks and C++ writes the response somewhere, Python goes and fetches it. You can also have a combination of languages. This might also require creating tables and structures in your database.

### Database Integration
You have your database and you begin to create maybe customer tables. You begin to create particular design. You've created your design. Then at this point, you begin to maybe do some connection, connect from your code written in Python or C#, and you see how you're able to seamlessly connect a particular database.

You could also use your Git kits. Remember, that's software that would also play out if you have developers scattered across different countries. You want to collect different updates from different developers. Your kit will help you track changes made by different developers. From there, your kit software will help you match.

Your kit would also track changes. Imagine if you have a particular version of software and there are errors quickly in your past, those changes made to that particular version. Your kit would help you do that. So that's the implementation.

## Testing Phase

That's implementation and you can see coding taking place here. Once you are done coding, the next task will be to test what you've developed. Do some testing where you are testing, verifying the software's stability, performance, and usability. These are the tests you carry out. Testing is carried out using a variety of methods.

### Types of Testing

We have different types of testing:

#### User Acceptability Testing
Users typically log into your application, in this case your e-commerce application, and they go through, they navigate and they act, receive - they are the customer. They log in and then they simulate that experience. They log in, they pick items from a catalog.

Once they're done with that, the next stage we need to go to a shopping cart and check out make payments. They also want to find out if that process is seamless. That's user acceptability testing.

#### System Testing
Testing by end users and system testing - that's another type of testing. Testing the complete system. As a developer, you'll begin to test, you will also log in, you carry out some activities just to find out if truly it reflects the requirements from your customer. That is also carried out.

#### Integration Testing
You also have integration testing - testing interaction between components. You would also find out if the functions can relate. Maybe you have a particular function responsible for making payment. Would it also work seamlessly with another function? It could be a third party function that processes that payment.

This is what your integration testing would find out - your ability to communicate, have that communication between particular function and another function. Integration testing tests that out.

#### Unit Testing
We would also have unit testing to test individual components or functions as you're testing individual functions. Imagine you've written a function to convert maybe kilometers to meters. You can write a test. The test is just like a function, right?

A function that would test that function. It could be using dummy data. There's a test to find out if indeed that function would conduct kilometers to meter or maybe that function would write something to a file. Component testing and your PieTest could be used in this regard. Therefore, doing unit testing. PieTest will be needed for unit testing.

So software testing. Once you are done testing and you scale that hurdle, customer testing during testing and different types of testing. Once you've scaled that, the next will be to deploy the solution.

## Deployment Phase

It is ready to go into deployment. After successful testing, the software is deployed to the production environment.

### Deployment Options

#### Local Deployment
Deployment could be on the server locally or on the cloud. I would discuss server at some point and different kinds of computers. You can have your clients, the customer can buy the server, and then that means you'll have to go to their environment to deploy that solution.

#### Cloud Deployment
Or your client can say, okay, well that solution, I want to host it on the cloud. In that case, you would have to buy space or infrastructure on the cloud, and your solution will be deployed on the cloud and the different platforms that can help you do that.

You have Windows hosting. You also have Windows Azure. You can also use Amazon AWS to deploy your solution to the cloud. AWS will host your solution - it has that infrastructure that could house your solution.

You can also use Apple tools. Different cloud platforms that you can leverage to host your solution.

#### Desktop Application Deployment
Deployment could also be sending the developed solution to clients' computers. So in that case, you're developing a desktop application. If it's something that would typically run on computers, individual computers, then that means you would have to go to your clients' facility and begin to install. Or you might teach them how to install. That means you have to send a file to them and they begin to install on different computers in their area.

## Maintenance Phase

That's deployment. Once you've deployed, you begin to maintain. There may be issues, there may be connection issues. Maybe your system is not able to connect to a legacy system. It could be protocol issues or the maintenance phase takes care of that.

The program has been deployed. In this state, problems are resolved - problems are resolved, your system is not able to connect. We are being called upon to rectify that. At this point would also fix defects.

### Maintenance Activities

Any necessary upgrades or improvements are made. Your clients can also request an update. In that case, you would have to do some notification to the code. What that means is that you have to push a different version to the cloud or to the client's facility. In this case, your server. That's maintenance.

Things can come up once you deploy your solution and it's your task to resolve those problems or errors or defects. Create some maintenance and you can also do your maintenance.

#### Cloud-based Maintenance
Imagine your solution is hosted on the cloud - that means you can do the maintenance remotely and push that update to the cloud.

#### On-premise Maintenance
But if the application is a desktop application, that means you would have to send that file to them and they begin to install the new version. For on-premise servers, the same thing applies. You have to go to your client's place.

If it's not connected to the internet, if you're able to reach it, that means you have to go to their facility, to the environment and deploy the new updates.
