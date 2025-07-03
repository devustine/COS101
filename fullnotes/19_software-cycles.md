# Software Development Life Cycle

## What is Software Development Life Cycle?

Software development life cycle is an organized method of creating applications. An organized method is structured, and so you want to develop your software systematically.

## Phases of Software Development Life Cycle

### 1. Requirements Gathering and Analysis

The first phase is to get requirements, collect requirements, and elicit requirements from your client. For example, imagine you have a client that wants to develop an e-commerce application. The first task would be to understand what kind of e-commerce the client would like to have.

Questions to consider include:
- Would they have a login page?
- Will customers make payments with their credit or debit card?
- What kind of user interface and payment system will be used?
- How will you arrange the products?
- How will you move from product to shopping cart?
- Can you move from shopping cart back to product?
- What security protocols will be used?
- How would people access your e-commerce application?

These are requirements you would have to gather. You reach out to stakeholders, end users, and clients to determine the software requirements. You collect requirements, and once you're done with that, then you begin to analyze your requirements.

The client might come up with tons of requirements. Your task is to look at those requirements and analyze whether they are ambiguous requirements. If they're ambiguous, you take them out. If something you're not able to implement, you'll also have to strike out or discuss with your stakeholder.

For example, you might want users to log in using a password, or you might want users to log in with their fingerprints or using facial recognition system. If you see that maybe facial recognition solution is not mature yet, or maybe there are errors in it, and clearly you can say during your analysis stage you can tell your stakeholders that you have to suspend the facial recognition system for the e-commerce application because maybe there's some errors or the accuracy is not close to a hundred percent. For that reason, your analysis will strike that out.

Then maybe you go for fingerprint authentication or using username and password. Your analysis will capture that, and you analyze and strike out ambiguous requirements or requirements you think you're able to implement.

During the requirements engineering phase, you can also record sessions so that you can be able to play back and do your analysis. You can record sessions so you can examine what you've recorded just to confirm what has been written.

### 2. Design Phase

Once you're done with that phase, you would move to a design phase. Just like civil engineers who want to erect a building, the first step would be to come up with a design - a layout, a plan. You have the kitchen floor, living room, dining room, and other sections.

Once you're done with the design, then you take that further and begin to erect the structures proposed in the design. Once you have a design and you're satisfied with the design, next will be to move to actual implementation, which is erecting walls to form your building.

In software development, you also have to come up with a design. During the design phase, you would typically encapsulate relationships between the functions. You imagine you have a payment function, and this payment function would also interface with third-party payment functions so that your design phase would encapsulate that kind of relationship.

You identify functions and functions you think will interact. You want to capture that relationship in your system design. For example, you have a payment function that will also interface with third-party software. Your design should also capture that relationship. So if you have your credit card information, you pass it into this function (payment function), that function would also interact with the third-party system. Maybe this third-party system would also interface with another system, and you have something that is returned - either denied or the payment went through.

These are the two possibilities. That interaction, you also want to capture that in your system design so you can see how various software functions or components would work together, and then how the system will be deployed to match the requirements.

At this point, you begin to discuss deployment. Are you going to deploy in the servers in the customer's environment, or are you going to deploy to the cloud? At the design stage, you begin to talk about this.

### 3. Implementation and Coding

After the design phase, you begin to implement. Implementation really means coding with a particular language. You can develop with Java, C++, C, or C#. You begin to implement, and programmers use appropriate programming languages, frameworks, and tools to write code in accordance with design standards.

You may have tools like Git (a version control system that tracks changes). You have software scattered across the globe and you're developing whatever you're developing, which would have to go into this tool. This would manage changes from across board changes made by software developers.

Programming languages that can come in handy in that software development space include Java, C++, C#, and Python. Depending on requirements, you can also mix languages. Your front end might be using Python interface, and have the back end using C++. You can also have two languages in that implementation phase. You have a group of developers using Python for the front end, and you have C++ doing the heavy lifting at the back end.

### 4. Testing Phase

Once you have the implementation phase and you have code, once you're done developing, the next will be to test your system. You want to know if it will reflect the requirements and gather testing for:
- Stability
- Performance 
- Usability
- User acceptability testing

Testing by end users means you have your e-commerce application and end users will test from the login phase or fingerprint phase. They have your login phase and from your login phase, the system also would allow you to browse through products. Once you're done, you pick items. From there, you go to your shopping cart. Once you're done with that, you go to the checkout phase. The requirement might also say that from your shopping cart, can you also go back to products?

You also test that out. You have your shopping cart, you have your checkout phase, and then you make payments, and then you have a thank you page. User acceptability testing - testing by end users. This is typically what would happen at that phase.

You also want to test the complete system. Testing by end users, and also encapsulating testing the complete system by software developers. Not only by end users, we also have software developers testing that process and ensuring that it meets the requirements of the stakeholders. Also testing the interaction between functions such as the payment function.

You want to test if you make payments - if you submit your credit card details here, that would send it to a secured function that does the payment and then returns the feedback. That interaction between functions, you can also test that out by putting in your credit card details and see if the payment will go through.

You can also test individual functions. Function might be a logging function - test that functionality. You could also test checkout function. The checkout would take you or typically take you to the payment page to test those components and functions.

### 5. Deployment Phase

Once you're done testing in the testing environment, then you deploy. In your design you might have captured that you will deploy in your client's environment, and you've captured that you will deploy in your client's environment.

For that reason, you would have to then deploy that solution in your client's environment. You have that deployment. It might be that you would also deploy on the cloud. In that case, you would have to rent a facility online. Then you have a space you rent and then you deploy your solution.

Typical cloud platforms are AWS (Amazon Web Services), Azure from Microsoft, and other cloud computing facilities you can push the application to. In this case of the e-commerce, you might want to persist data - customer's data, you want to persist that. You want to store that in a database. In that case, you might also have, for example, your Microsoft SQL Server.

You have that and you put that there and you have that connection to your e-commerce, and it connects with the database to persist the information or items. The same thing applies. You have this on the internet, on the cloud, you can also have your database where information data from the e-commerce application will be moved to.

You can see that the migration, the integration, and then you begin to do some training too. It's a new system, so you begin to train people how to use the e-commerce application in this case. So while you are deploying, you are also doing some system integration.

In this case, you are integrating with legacy systems - existing systems. How will this new system connect with legacy systems? These are things you look at at a different stage. You can also run this in parallel to where you're deploying. You can also train users to those that will use that system.

Then you can train them. Employment deploying. This could be in the user's environment or it could also be that you're pushing to the cloud. You have the software here to try to connect to a remote cloud facility.

### 6. Maintenance Phase

Once you're done with the deployment, you would have to do some maintenance. At this stage, the maintenance phase begins after the program has been deployed. Then you begin to resolve problems.

You have defects to fix - maybe this particular new solution, the e-commerce solution wouldn't talk to a legacy system. It's your duty to come in and ensure that you have that seamless flow. You can do that during maintenance and any upgrades.

Your customers or stakeholders might also demand upgrades. You can carry out that during the maintenance phase - you have improvement. Improvements are made at this phase. So maintenance - you fix things, you fix defects.

Things that might crop up that might block a seamless flow. Imagine it's a new system with a legacy system. It's your ability to play that out, and so that's maintenance.

## Software Development Methodologies

So we've looked at all the phases. We've looked at requirements gathering. Once you gather requirements, you begin to design. Once you do your design, you begin to develop code. Once you code, you test. Once you do some testing, you deploy, and you begin to maintain. How do we do these maintenance?

That is what methodology speaks to. Software development methodology and development techniques are the different methods and frameworks that teams and organizations use to organize, carry out, and complete tasks. How do we organize these phases?

That is what software development methodology speaks to. How do we organize these phases? Do we organize it from top to bottom, or can the organization be such that it's flexible?

We have two kinds of arrangements:

### Waterfall Methodology

Waterfall is a methodology and it speaks to how you arrange your software development process. Waterfall methodology is a sequential and linear process.

Before going on to the following phase of the software development life cycle, each phase must be finished. At the onset, requirements are gathered, and the entire project is planned and recorded. The approach is unbending and less flexible.

You can see it goes from top to bottom, hence waterfall - waterfalls from top to bottom. You gather your requirements. It could be for three months or two months. Once you're done with that, you begin to design. Once you're done with the design phase, you begin to develop. Once you're done with that, you begin to test. Lastly, you begin to deploy.

The downside to this approach is that it's not flexible. What that means is that if you haven't captured requirements sufficiently and you move to the design phase, you cannot go back to the requirement phase. You have to go from top to bottom. It's not flexible.

That means you have to get your requirements right. Once you're done with that, you go to the design phase. If you would want to capture more requirements, then the waterfall approach will not be suitable because you cannot go back to a previous phase.

### Agile Methodology

Agile methodologies emphasize intuitive and incremental development, intuitive goals and cycles. The project is divided into smaller iterations or springs. Instead of gathering all the requirements as seen in the waterfall, agile will take, will prioritize requirements, take the small requirements, and then roll through that route.

Take small requirements, design, develop, test, and deploy. You can see the project is divided into smaller iterations or screens, typically ranging from one to four weeks.

The requirements and priorities can be adjusted through the project, and so it's flexible. However, this approach may not support documentation because things are done so fast that paperwork might be ignored. Paperwork such as requirements documents might not be detailed. Your design might not be detailed.

Unlike waterfall, where you spend so much time during that requirements gathering stage, typically three months or even more four months, you are able to get that sufficiently and you're able to do that paperwork. You move to the design, you can also spend that design. You can spend up to four months, you have so much time, then you begin to document.

But for agile, typically you can see now it runs to your deployment, your requirements to testing, to deployment can go within one to four weeks. So it's flexible. So if you have requirements that are changing, then clearly agile methodology would be appropriate.

But if you have requirements that are really stiff that wouldn't change, or maybe you've got enough requirements and you think that you can move on with that, then your waterfall would suffice.

However, this approach may not support documentation. So that's the downside to agile methodology.

## Agile Methodology Cycles

You also collect new requirements for the next cycle. Each cycle might be around one week to four weeks.

You collect another set of requirements. You design, deploy, test, and also deploy again, implementing whatever you've collected during the testing phase. Then you review again, you look at the next requirement, and you design. So you go in cycles - you can see it's an iterative methodology.
