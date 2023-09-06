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

> IOS and Android platform.
  Node.JS/React
  Database to store user data.
  Security to protect user financial data.

- Would you have to learn a new technology?

> Yes having a secure API to use.

- What would MVP look like (use user stories)

> As a user, I can create an account.
  As a user, I can manually input my daily transactions.
  As a user, I can see the rounded-up change added to my savings balance.

- What are the app milestones

> User registration and authentication
  CRUD functionality.
  Basic User Interface.

- What other things need to be considered about this app?

> Data security to ensure user financial data is encrypted and secure.
  Complying with regulations for linking banks.
  User interface is user-friendly and fluid.
  Mobile compatibility.

- Is this app idea feasible for a hack-a-thon?

> No because getting the bank to link to a bank potentially will take a while.

- Can you adapt this idea to make it more feasible for the timeline?

> Yes you can work on user interface with manual transaction input feature and make it fluid and sleek along with leaving bank integration for a future change.

- How could you encourage users to interact with this app regularly?

> Send weekly notifications with savings progress.
  Set milestones for saving a certain amount.
  Offer rewards or "dailies" for everyday usage.

- How could people misuse this application?

> User can input false data to lie about how much theyre really saving.

- Are there any safety issues with this application?

> Protecting user financial data is crucial
  Ensure every user transaction is confidential
  Comply with financial regulations and data laws

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> Node.js/React.
  IOS and Android.
  Real-time chat.

- Would you have to learn a new technology?

> Real-time Chat

- What would MVP look like (use user stories)

> As a user, I can log in and create an account.
  As a user, I can select a topic and mood for a conversation.
  As a user, I can randomly match with a user.
  As a user, I can engage in text or voice chat.
  As a user, I can rate the quality of the discussion.

- What are the app milestones

> User registration and authentication
  Topic and mood selection
  Matchmaking algorithm
  Real-time chat
  User rating system
  Basic user interface

- What other things need to be considered about this app

> User data privacy.
  A report button and moderator to judge wether a person should be banned.
  Server scalability to handle potentially large amount of users at one time.

- Is this app idea feasible for a hack-a-thon?

> No because getting real-time chat to work within a dat is not feasible.

- Can you adapt this idea to make it more feasible for the timeline?

> Focus on text chat only and leav voice chat as a future change.
Use pre-built real-time chat libraries to save developement type.
Simplify moode selection to speed up developement.

- How could you encourage users to interact with this app regularly?

> Implement milestones and rewards for daily use.
  Show notifications on trending moods or topics.

- How could people misuse this application?

> Inappropriate or offensive conversations.
  Trolling, and spamming, and cyberbullying.
  Users trying to find eachother outside the app.

- Are there any safety issues with this application?

> Breach in security and show user information.

