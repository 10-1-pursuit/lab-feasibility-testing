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
    1. Mobile App Integration for Apple/Android OS.
    2. Push Notifications (via mobile or email)
    3. Secure database to hold user data and protect financial details.

- Would you have to learn a new technology?

> Your answer here...
    Yes, push notifications have their own timing and usage and it would be a matter of finding a secure Third party storage for user data.

- What would MVP look like (use user stories)

> Your answer here...
    1. As a user I can create an account and update my profile.
    2. As a user I can create a personal milestone or goal to save to.
    3. As a user I can see the total change saved in a day, week, or month.

- What are the app milestones

> Your answer here...
    1. Functional UI with navigation
    2. User Registration and Welcome.
    3. Total update on main page.


- What other things need to be considered about this app?

> Your answer here...
    1. Security and encryption
    2. Bank connection/authorization
    3. Identity confirmation

- Is this app idea feasible for a hack-a-thon?

> Your answer here...
    For a hack-a-thon? No, there's no way to complete something of this scope with the permissions needed in a two day timeline. As a shell/proof of concept? Possibly, but it'd be bare bones. 

- Can you adapt this idea to make it more feasible for the timeline?

> Your answer here...
    Likely making this a 'set your own goal' app, with manual user input of change/transactions throughout the day and a calculation of how much should be set aside to save.

- How could you encourage users to interact with this app regularly?

> Your answer here...
    Push notifications would go fairly far with this; as well as goal bonuses or a double rewards
    for "streaks".

- How could people misuse this application?

> Your answer here...
    Data can be accessed about banking information, routing, leading to identity theft if proper security measures and authentication are mishandled.

- Are there any safety issues with this application?

> Your answer here...
    Yes, as stated previously, without major security measures at play, both user and banking partner details could be easily accessed and abused or sold.

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> Your answer here...
    1. Real time text chat
    2. VoIP protocol
    3. Mobile Integration.

- Would you have to learn a new technology?

> Your answer here...
    Yes, you would have to learn live chat and voice synch. 

- What would MVP look like (use user stories)

> Your answer here...
    1. As a user I can create an account and log in.
    2. I can select a topic and mood for a conversation with anyone.
    3. I can be matched with someone based on that topic anonymously in voice or text chat.
    4. I can rate the quality of my experience after.

- What are the app milestones

> Your answer here...
    1. General Topic Selection
    2. Real Time Chat
    3. User Interface
    4. Rating/Improvement system.
    5. Randomized matchmaking system.

- What other things need to be considered about this app

> Your answer here...
    Privacy and report protocols. Additionally a required age check or permissions from a parent/guardian to prevent minors from being exposed to potentially adult topics. 

- Is this app idea feasible for a hack-a-thon?

> Your answer here...
    No, real time chat is complex to handle within the short time of a hack-a-thon; and there's too many ways for chat lines to be left open, leaving security breaches available.

- Can you adapt this idea to make it more feasible for the timeline?

> Your answer here...
    Implementing an AI chat bot to respond? Focusing solely on text chat rather than VoIP connections and simplifying anonymity by cutting out user login. 

- How could you encourage users to interact with this app regularly?

> Your answer here...
    1. Showcasing new themes and moods based on popularity in discussions, or polls.
    2. Push notifications about user-submitted topics when someone selects them.
    3. Daily streaks for chats.

- How could people misuse this application?

> Your answer here...
    1. Exploitation of information, cyberbullying.
    2. They could worm their way through the backend and trace IP or location leading to vulnerabilities for users of all ages.
    3. Text chat specific: code can be sent through and break the application. 

- Are there any safety issues with this application?

> Your answer here...
    A great deal of security issues. Age restriction, topic monitoring, moderation, secure encryption would all be needed in order to make this even remotely safe for general use.
