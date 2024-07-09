# JPMC Task 2
Starter repo for task 2 of the JPMC software engineering program

## Set up
Just like in the last task, you need to get your local development environment up and running. Given that you completed task 1, you should already have python installed and be familiar with git.

1. First, fork and clone this project repo.
2. In this task, we will be working with javascript in addition to python. Javascript has a handy package manager called npm, which handles package tracking, discovery, installation, and removal. We will be using it to install a series of javascript dependencies to your machine. If you already have access to npm on your system, you can skip this step. Otherwise, you will need to acquire it by following the instructions here (npm comes bundled with nodejs): https://nodejs.dev/en/learn/how-to-install-nodejs/. For this project to work, you must have node 18.10.0 installed on your machine. Ensure you have the correct version by running “node -v” in your terminal. If you do not, consider using nvm to install the correct version for you.
3. Install the necessary dependencies by running `npm install` from the project repo.
4. Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo)
5. Start the client by running `npm start` from the project repo

## Now it's time to make changes!
Here is an example of what this task looks like in the form of an engineering ticket.

### Purpose:
- The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application. Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.

### Acceptance Criteria:
- This ticket is done when the graph displayed in the client-side web application is a continuously updating line graph whose y-axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph should be the result of continuous requests and responses to and from the server for the stock data.
- This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server
