# Feasibility Testing

## Getting Started

1. Fork and clone this repository.

1. Answer the questions below by editing this readme. Leave the questions and prompts, and answer in between them. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

1. Where applicable, add screenshots, photos, and links.

## Instructions

You will check the feasibility of two app ideas and determine a better option for a 2-day hack-a-thon project.

The hack-a-thon starts on a Friday. You spend 2 hours meeting your group, coming up with ideas, and planning.

The expectation is for everyone to code from 9am to 9pm Saturday and from 9am to 6pm on Sunday, with presentations from 6pm to 9pm on Sunday.

## Idea One: Save the change

Concept: Saving money is challenging, but what if you could do it in small ways daily?

A user will round up the amount spent for every purchase made and put the change into a savings account. For now, the user must manually enter the amounts in the app. But eventually, connecting to banks and credit cards to automate the process would be the next step.

- What technologies are needed?

> Technologies required are a mobile application builder to allower users to input change amounts, a calculator functionality that uses a JS function that rounds up the change. It will also require User Interface design including prototyping, wireframing and adding menu/navigation bar, forms, and buttons to help users navigate successfully. It will require financial institutions to provide APIs or SDKs in order to link with credit cards and bank accounts. Technology such as SQL to build a database that stores user accounts and technlogy like OCR (Optical Character Recognition) will be necessary to extract transaction details from receipts.

- Would you have to learn a new technology?

> Yes, you would need to learn a mobile application builder software and learn the coding language for that software. You would also have to look into credit and banking transfer services. Since we’re dealing with personal and financial information, we would require implementing security features such as, OAuth, or secure authentication to protect financial data and user privacy, encryption, security audits. 
There are also financial institutions like Plaid, Stripe that can help facilitate transactions. It's also required to learn SQL to store user accounts. 


- What would MVP look like (use user stories)

> As a user, when I launch the mobile app I can create a new account with a username and password.

As a user, I can log in my account successfully.

As a user, I can change my password if I forget it.

As a user, I can manage my account and navigate the menu bar easily.

As a user, I can view and make changes to my personal, and financial information. 

As a user, I can access and learn about various products/services.

As a user, I can add a service or product.

As a user, I can access my account, and transaction history.

As a user, I can take picture of receipts with my mobile phone, and capture receipt details.

As a user, I can view the scanned receipt data, and confirm the data.

As a user, I can submit the transaction and see the changes made to my savings account. 

- What are the app milestones

> Gather appropriate funding to build the app.
Learn and have access to the necessary software, app builder, programs/services,
that will assist in building the app.

Assemble a development team willing and eager to work together.

 Obtain the API/SDK keys. 

 Build the UX/UI; wireframing, design and visual assets.

App Development: Writing the code and building components and app functionality.

Complete a working, functional version of the app for testing.

Refine the app's functionality, and design and release a Beta version.

After testing and reviewer feedback, Address functionality issues, bugs, and refine the app further. 

Publish the app and distribute it to app stores (Apple App Store or Google).



- What other things need to be considered about this app?

> Building the app's brand, market the app, acquiring the licenses and subscriptions to Plaid, Stripe and other financial institutions. Learning SQL to store user data. 

- Is this app idea feasible for a hack-a-thon?

> I wouldn't consider a ready, working app version of this concept feasible. However, a basic design with limited features is definitely feasible but it depends on various factors including; the complexity of the app, development team's skills, if the APIs/SDKs are accessible, if there are quicker, easier-to-learn programs and libraries or frameworks that will reduce learning curves.    

- Can you adapt this idea to make it more feasible for the timeline?

> Yes, you could make an app with limited features. 

- How could you encourage users to interact with this app regularly?

> Don't waste your change. Every little cent saved can be a financial opportunity to gain interest or be invested. 

- How could people misuse this application?

> This application could be hacked or personal data can be leaked. Otherwise, this app can be safely operated and used. 

- Are there any safety issues with this application?

> Only security breaches and possible hacking. 

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?


> React to help build the app
Cloud services for hosting
The use of Websockets technology to implement a Real-Time Chat functionality
A database for conversation topics
Reporting and moderation technology to report abusive behavior.
End-to-end encryption
User ratings technology

- Would you have to learn a new technology?

> Not necessarily because you’ll be using React mostly to build the app’s infrastructure, and discover how to implement chat functionality into your app. 

- What would MVP look like (use user stories)

> As a user, I can sign up and enter my username and password.

As a user, I can select a variety of topics and interests that I feel comfortable talking about.

As a user, I can choose wether I’m looking for a friend, or a possible date or just to waste a few minutes chatting.

As a user, I can choose age, gender and location of the person I want to chat with.

As a user, I can rate my conversation and the person I spoke with. 

- What are the app milestones

Design a functional app with input forms, sign-up and account login features.

Allow for users to create and stylize their profile cards (optional) 

Build a user-friendly design

Implement a functional real time chat feature

Set a database for topic choices and build a form that enables topic selection

Implement a feedback or rating systems

- What other things need to be considered about this app

> Encrypting personal information.
How much does Webstock charge for chat systems?
Should it be a free app? Subscription?

- Is this app idea feasible for a hack-a-thon?

> Yes, the idea is very simple and basic. It’s possible to do it within a few hours or a day. The components are not overly complex and time consuming. There is also no learning curve.

- Can you adapt this idea to make it more feasible for the timeline?

> The app is doable within the timeframe. If you really wanted to reduce more time, you could remove the feedback/rating system. 

- How could you encourage users to interact with this app regularly?

> Are you stuck somewhere, bored, or have a few minutes to spare? Would you like to spend that time chatting with a random person? With no strings attached? 

- How could people misuse this application?

> People will most likely troll others, pretend to be someone they’re not, ask for personal information, send inappropriate content, say negative or hurtful comments, scam or use it to scam. 

- Are there any safety issues with this application?

> Yes, users could use the app inappropriately, scam or steal personal information. People could use the app to troll others, hurt people’s feelings, say provocative comments or send inappropriate content. This can be unsafe for mental health, and place people in physical danger if used incorrectly. 
