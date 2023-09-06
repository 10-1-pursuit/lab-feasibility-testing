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

> Your answer here...
You could incorporate an secure API to connect to the users bank account that would securely communicate with the app to transfer the rounded up amount to the users savings account. 
(Such as Plaid API)

- Would you have to learn a new technology?

> Your answer here...
In this case reading the plaid documentation and learning to have it communicate with the users bank account would probably suffice but nothing too inherently new.

- What would MVP look like (use user stories)

> The users would be able to create an account and link their bank account to the app. The app would then round up the amount spent for every purchase made and put the change into a savings account. The user would be able to see their savings account balance and the amount of money they have saved up.

- What are the app milestones

> a) Users can create an account and log in. b) Users can link their bank account to the app. c) The app would then round up the amount spent for every purchase made and put the change into a savings account. d) The user would be able to see their savings account balance and the amount of money they have saved up.

- What other things need to be considered about this app?

> Edge cases where banks aren't connect to the app or the app doesn't have access to the users bank account. Also the security of the app and the users bank account information.

- Is this app idea feasible for a hack-a-thon?

> The bare functionnality of the app is feasible for a hack-a-thon but the security and bank account connection would be a bit more difficult to implement in a hack-a-thon.

- Can you adapt this idea to make it more feasible for the timeline?

> Yes, you first start with the bare functionnality (possibly have the user set a regular deposit based on budget to their savings) of the app and then you can add the bank account connection(to make it transfer round up on individual transactions) then make sure every aspect is secure later.
At that point it would be beta testing and debugging before release.

- How could you encourage users to interact with this app regularly?

> People tend not to like to be pressured about their financial health they don't want to feel that they are not doing enough with their money. I would actually advertise the app as a one and done set up and then let the app do the work for you. Simple notifications that congratulate them at random for setting up any saving options would more than prompt them to open the app check their savings and maybe use more functionnality. I would also have a feature where the user can set a goal for the amount of money they want to save and the app would let them know when they have reached that goal.

- How could people misuse this application?

> I can see third parties misusing the app to get access to the users bank account information.

- Are there any safety issues with this application?

> The safety issues would be the users bank account information being stolen or misused.

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> Real-time communication protocols such as XMPP (Extensible Messaging and Presence Protocol) or WebSockets for ensuring quick message delivery and synchronization across devices.

Cloud-based storage solutions for storing chat histories and multimedia files.

Encryption protocols like SSL/TLS or end-to-end encryption to ensure the security and privacy of user data.

APIs and SDKs provided by chat platform providers like Twilio or Firebase to simplify the development process

- Would you have to learn a new technology?

> Incorporate these technologies in a web applications with a React frontend and a Node.js backend.

- What would MVP look like (use user stories)

> Users can create an account and log in. Users can select a topic and a mood. Users can be matched with another user. Users can text chat with another user.

- What are the app milestones

> a) Users can create an account and log in. b) Users can select a topic and a mood. c) Users can be matched with another user. d) Users can text chat with another user. e) Users can voice chat with another user.

- What other things need to be considered about this app

> Edges cases for the chat app would be the users being matched with someone they don't want to talk to or someone who is not in the mood to talk. Also the security of the app and the users identity being discovered.

- Is this app idea feasible for a hack-a-thon?

> It could take a lot longer than a hack-a-thon to implement the app.

- Can you adapt this idea to make it more feasible for the timeline?

> First we could start with regular chat rooms with a topic and mood and then we could implement the random matching and then the voice chat.

- How could you encourage users to interact with this app regularly?

> Ask them to setup a reminder at the time they are most likely to use the app.

- How could people misuse this application?

> rude and harrasing messages if the users pool is not too large and the users are not anonymous.

- Are there any safety issues with this application?

> Criminals could use the app to lure people into dangerous situations.
