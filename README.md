This document starts a step-by-step walkthrough. The next part is a description of the tool and when you might use it. The last part talks about further development in the works and how you can help.

# 1. How to Use

Starting out, you have three tasks:
### 1. Input the question you're trying to decide on. Good questions include:
  - "Where should we order dinner from?"
  - "Should we wear masks to the party?"
  - "How should we get home from the demolition derby?"
  - "What game should we play?"
  
### 2. Pick the way you would like to decide:
  - Random selection is great when no one feels strongly about any options.
  - Decide by Voting is best when you only have a couple of options.
  - Decide by Ranking is fantastic when you're trying to narrow down ideas from many in a large group.
  
### 3. Check or Uncheck the option to allow voters to reject an idea:
  - This gives people a chance to reject an option if they aren't comfortable saying so directly to the group.
  - This option is *not recommended for groups smaller than 5 people.*
  
After clicking "Let's Decide", you will be brought to a page where the actual decision process will take place!
### 4. The next step is inputting everyone's ideas:
  - One person can input for the group or everyone can be given a chance to add their ideas
  - Once all ideas are added, please click the "Finish Adding Ideas" button.
  - If random selection used, click Let's Decide to find out your decision!
  
### 5. Now a voting window should appear- give everyone a chance to fill it out:
  - Names are required to discourage double voting.
  - Default options are random for all votes and no for the rejecting vote line.
  - When ranking, it should not allow the same option to be selected twice.
  - Click "Conclude Voting" when everyone has voted.
  
### 6. Click Let's Decide!
  - You can see what everyone's top pick was before clicking though!
  
### 7. "Clear Ideas & Reset" reloads the page so that you can add new choices.

### 8. If the group is happy with the choices, but unhappy with the results, click the buttons that start with "Use ..." to try to decide again.

*Please send feedback if you have any issues, want something changed, or like something in particular!*
  
# 2. Description
  The idea behind *Decide* is to take the difficulty out of making small group decisions like where to eat, what game to play, or what activity to do. The basic process is that you first state what the question is that you're trying to answer, which is then followed by everyone submitting their ideas. After that, people can optionally vote and/or reject ideas before the program selects an answer for the group. Options are available at the beginning to allow the group to choose whether they want to vote or just have a random decision between the options they come up with. Overall, *Decide* has been made with the intention of making the process as easy as possible while also trying to minimize the number of ways that people can game the system so that the group can get a fair decision.
  
  **This tool is not meant to make important decisions** and should not be used for significant decisions, such as how many children to have, what country to move to, or how much to bet on the Pinewood (or Kentucky) Derby. It's **intended for daily use in social situations** like deciding *where to go for lunch* with your friends or which streaming service to buy if you must stay home for months.
  
# 3. Development

Any problems, comments, or ideas are greatly appreciated. I made this because I don't like spending half an hour trying to figure out what everyone has eaten in the last week to try to agree on where to eat dinner with a group. I hope you find other uses for this and let me know so that I can make it better for your daily questions. You can reach me at wtharvey2@gmail.com.

### 3a. Known Bugs
- Duplicates remain for inputting ideas if cases are different (i.e. "A" and "a" do not
  get sorted into the same vote option)
- In the server, null scores sometimes appear; at the same time, it appears the client doesn't correctly set the screen.

### 3c. Future Feature Ideas
- Live Updating Votes and Ideas
- Use a database instead of storing info on server instance
- Presets where you can save options for repeated use.
- Easier-to-use interface (open to suggestions for what this may look like)
- Ways to use external files or data to provide options (like if you have a spreadsheet of restaurants you like)
