# JPMC Task 3
Starter repo for task 3 of JPMC's Forage program

## Here is the background information on your task
Being able to access and adjust data feeds is critical to trading analysis and stock price monitoring. With the prior tasks complete, we have the adjusted data set up on your system and piped into Perspective.

For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstations.

Given that an enormous amount of information and data are produced at once, visualising data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

## Here is your task
In this task you'll accomplish the following:
- Set up your system by downloading the necessary files, tools and dependencies.
- Modify the typescript files in the project repo to make the web application behave in the expected manner

## Set up
Just like in the last task, you need to get your local development environment up and running. Given that you completed task 1, you should already have python installed and be familiar with git.

1. First, fork and clone this project repo.
2. In this task, we will be working with javascript in addition to python. Javascript has a handy package manager called npm, which handles package tracking, discovery, installation, and removal. We will be using it to install a series of javascript dependencies to your machine. If you already have access to npm on your system, you can skip this step. Otherwise, you will need to acquire it by following the instructions here (npm comes bundled with nodejs): https://nodejs.dev/en/learn/how-to-install-nodejs/. For this project to work, you must have node 18.10.0 installed on your machine. Ensure you have the correct version by running “node -v” in your terminal. If you do not, consider using nvm to install the correct version for you.
3. Install the necessary dependencies by running `npm install` from the project repo.
4. Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo)
5. Start the client by running `npm start` from the project repo
