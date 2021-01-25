# chatbot-sample

<details><summary>Click to Read Challenge</summary>
This exercise is to help us determine your ability to write quality, self-documenting code, pay attention to edge cases, and follow requiremetns. You have 48 hours to submit your project from when we provide you access to this repository. It also checks your ability to use Git...

INSTRUCTIONS

1. Clone this (mostly) empty repository
2. Create a branch with the pattern AUS_FirstName_LastName
3. Write your project, be sure to include unit tests! Please include any databse sql files (including DDLs for any tables/views/functions/etc that you necessary to run your code)
4. Be sure to squash commits if you have more than 1 commit to your local branch.
5. When finished create a pull request against the develop branch, do not merge. Send your recruiter the link to your PR. Your recruiter must receive the link no more than 24 hours after you have been given access to the repo.

REQUIREMENTS

Create a simple chat bot.

The goal of this exercise is create a simple chatbot that interacts with the user, asks questions and process responses. Based on the response, the chatbot should perform an action. The chatbot should be able to handle erroneous responses by clarifying and restating the original question. For the purpose of this exercise, the chat can occur completely in the console window, bonus points if the chat occurs in a form window. The task is to implement the following chat workflow in the attached pdf file.

Each conversation node is expecting a particular data type – Boolean, String, etc. Based upon the response, the chatbot should respond according to the document. Please note that all nodes expecting a response should be able to hand bad responses and respond appropriately. Also, there are some responses on all nodes that have the same response (such as CANCEL). For each action, log the response (this is to simulate taking some action beyond continuing the chat)

We will be evaluating your project on adherence to requirements, data structures, and clean code. The most elegant solutions will focus on the data structure that supports a configurable conversation, that is, the actual text of a conversation node should be configurable via a text file, database record etc. Also, your solution should be able handle/support changing the flow of a conversation. Not a requirement for this implementation – but be able to explain how to add/remove/modify conversation nodes without requiring code changes.

Be sure to include unit tests...(sigh)

Please use Java to implement the solution as the role will be heavily using Java on the job….

</details>

## Implementation

- Product workflow required only recursive programming, undertook a more challenging initiative to engineer a text-based game.
- Was under the impression this was a NodeJS/JavaScript/React position?
- Cleaned up the design PDF for legibility, all yours for reuse.

## Solution Demonstration

- Install [NodeJS](https://nodejs.org/en/), if not already installed.
- Clone repository directory to local.
- Run `npm install` from cloned diretory in terminal.
- Run `node index.js` from cloned directory in terminal.
- Observe console prints and respond accordingly to game bot or accept defeat.
