# JPMC Task 3
Starter repo for task 3 of JPMC's Forage program
 #
# BACKGROUND INFORMATION

Being able to access and adjust data feeds is critical to trading analysis
and stock price monitoring. With the prior tasks complete, we have the
adjusted data set up on your system and piped into Perspective.
For traders to have a complete picture of all the trading strategies being
monitored, several screens typically display an assortment of live and
historical data at their workstations.
Given that an enormous amount of information and data are produced at
once, visualizing data in a clear manner with UI/UX considerations
accounted for is critical to providing traders with the tools to improve their
performance
#
# TASK BRIEF

In this task you'll accomplish the following:
1. Set up your system by downloading the necessary files, tools and dependencies.
2. Modify the typescript files in the project repo to make the web application
behave in the expected manner
3. Generate a patch file of the changes you made.
4. Submit your work
#
# SETTING UP DEV ENVIRONMENT

Just like in the last task, you need to get your local development environment up
and running. Given that you completed task 2, you should already have python and
node installed and have at least a marginal familiarity with git

1. First, fork and clone the project repo (Folder available in Task Resources folder)
○ Remember to uncheck the “Copy the main branch only” box in the fork
dialog on github. A model answer has been provided in a separate branch
from main.
○ Create a new virtual environment in the project root. Pycharm can do this
automatically for you using the “configure python interpreter”
(https://www.jetbrains.com/help/pycharm/configuring-python-interpreter.html)
option in settings.
○ Install all project python dependencies. These are listed in the requirements.txt
file.
2. Install the necessary dependencies by running `npm install` from the
project repo
3. Recall that you must have node 18.10.0 installed for this step to work
correctly
4. Start the python server by running server3.py from the project repo like so:
python datafeed/server3.py (note it’s important you run it from the root of
the project repo)
5. Start the client by running `npm start` from the project repo
#
# MAKING CHANGES

When you’re in a work environment, you’ll usually receive tasks in the form of
engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.
Purpose
You will use perspective to generate a live graph that displays the data feed in a
clear and visually appealing way for traders to monitor.
Recall that the purpose of this graph is to monitor and determine when a trading
opportunity may arise as a result of the temporary weakening of a correlation
between two stock prices. Given this graph, the trader should be able to quickly
and easily notice when the ratio moves too far from the average historical
correlation. In the first instance, we'll assume that threshold is +/-10% of the
12-month historical average ratio.

Acceptance Criteria

● This ticket is done when the numbers from the python script render properly in
the live perspective graph. That means the ratio between the two stock prices is
tracked and displayed, the upper and lower bounds are shown on the graph, and
an alert is shown whenever the bounds are crossed.

4.1 Instructions for completing the task are included in the Task 3 - Step-by-step
Guide

4.2 When you’re finished, commit and push your changes to your forked repo, then
Upload your git patch file. To generate a patch file, you may follow the given
guide.

ADDITIONAL RESOURCES
1. JPMorgan Chase’s Perspective - https://jpmorganchase.github.io/perspective/
2. GitHub Page for Perspective - https://github.com/jpmorganchase/perspective/
#
