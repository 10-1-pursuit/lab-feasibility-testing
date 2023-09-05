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

> An app 
    > JavaScript, CSS, HTML, React
    > A calculator to caluculate the totals saved
    > A place to store the values of what's saved
    > Purchase history to see what was spent/what was rounded up
> Login-in possible

- Would you have to learn a new technology?

> From the technologies listed above no, however when implementing the connection to banks and credits cards it is possible a new technology may need to be learned. 

- What would MVP look like (use user stories)

> A user can enter the amount of the purchase.
> A user can enter the amount rounded up from the purchase to be saved.
> A user can calculate how much they have saved.
> A user can see how much they have saved in total. 

- What are the app milestones

> Entering purchase amounts works
> Entering amounts to be saved works
> Calculator works
> Ability to view totals entered works

- What other things need to be considered about this app?

> Will the user need to log-in to use/view app
> Security concerns about who can view/edit the users information in the app

- Is this app idea feasible for a hack-a-thon?

> Possibly, if there is a larger development team and tasks are spread out amongst the team. If the development team is on the small side like stated in the notes as 4 people, I don't think it is feasible for this time frame.

- Can you adapt this idea to make it more feasible for the timeline?

> If possible use an already built calculator within the app instead of having to create that functionality. It would save on time.

- How could you encourage users to interact with this app regularly?

> Add an alarm or notification feature that would remind the user daily
> Have an incentive that offered something when a user saved a certain amount in a set period of time

- How could people misuse this application?

> Since they have to manually enter the information, user error such as entering the wrong amount and/or miscalculations may occur.

- Are there any safety issues with this application?

> Yes, if it's not required to log-in with a secure username and password someone who's not the user could get into the app and see or even change what a user has saved.

> **Note**: For a hack-a-thon, imagine you are a team of 4 people, so try to plan the milestones knowing that multiple people are contributing.

## Idea Two: Random Chat app

Concept: People are busy and lonely; what if they could get on a chat app, select a topic, and be randomly matched with someone who wants to discuss the same thing?

A person logs in and selects a topic (houseplants, the weather, the meaning of life) and a mood (cheery, argumentative, silly, etc.). They are matched with another person and can do either text or voice chat. At the end of the conversation, users rate their discussion.

It is anonymous; no pictures, real names, or locations are shared. Once the connection ends, there is no way to connect with that person again (unless they get matched again, randomly).

- What technologies are needed?

> An app 
    > JavaScript, CSS, HTML, React
    > A way to text chat or voice chat
> Database
    > API that contains different topics the user can pick from
    > Moods to pick from
> A way to match based on selections & mood
> A way to rate experience
> Log-in should be required

- Would you have to learn a new technology?

> Not with the technologies above

- What would MVP look like (use user stories)

> A user should be able to log-in
> A user should be able to choose whether to chat through text or voice 
> A user should be able to choose a topic to discuss
> A user should be able to choose a mood 
> A user should be able to be randomly matched with another person
> A user should be able to chat
> A user should be able to rate the experience
> A user should be able to expect to be anonymous


- What are the app milestones

> Log-in works
> Text chat works
> Voice chat works
> Topics can be chosen
> Mood can be chosen
> Match randomly based on choices works
> Rate experience works
> Anonymity functionality works  

- What other things need to be considered about this app

> Ability for chats to be moderated to ensure no bullying, threats, or harassment

- Is this app idea feasible for a hack-a-thon?

> No, there a lot of moving parts. This timeline doesn't leave room for challenges that may arise to have time to be fixed. 

- Can you adapt this idea to make it more feasible for the timeline?

> Possibly outsource a lot of the app functionality for random matching, voice chat, text chat, and rating experience. 

- How could you encourage users to interact with this app regularly?

> Add notifications to remind user about the app
> Have incentives for using the app, for example offering something for every 10 chats rated.
> 

- How could people misuse this application?

> Because it's anonymous some people could be more likely to use it to bully, threaten or harrass others. 

- Are there any safety issues with this application?

> Possibility of it being hacked and no longer being anonymous
> If their is no age verification required, possiblity of minors getting on and using the app
