# Density Fullstack Homework Assignment

## Goal
Your goal is to build a web application that displays the latest "heartbeat" from a number of sensors.

## Assignment
Your task is to accomplish the following:
- We use Golang, Typescript, Rust, and Python (with the associated frameworks). We would prefer you to choose from one of these, but if you strongly prefer other languages please ensure that the project is well documented and can be run on someone else's machine.
- Use your language of choice to build a web application
- Scaffold a database that includes sensors (think Density Open Area and Entry sensors) and heartbeats
    - A sensor is a device in the field.  It generally includes a serial number and other metadata
    - A heartbeat is a periodic message used to tell the backend that the sensor is online and provide the current state of the sensor
    - It is left as an exercise to the candidate to define exactly what data is stored (as well as how it is stored) for a sensor and a heartbeat 
- Expose an endpoint that can receive "heartbeats" indicating that the sensor is alive and checking in
- Deliver a webpage where a user can view live, updating heartbeats from the sensors. 

Bonus Points: Build or tell us how you would include a way to alert users if a sensor hasn’t sent a heartbeat in the last 10 minutes.

## Fullstack Position
If you are applying for the Fullstack position, please follow the assignment above with the following modifications:

* Use a frontend framework like React for the UI (or vanilla js if you prefer), ideally make the page realtime

## Backend Only Position
If you are applying for a backend only position, please follow the assignment above with the following modifications:

* It is not required to use a front-end framework such as react for the UI.  Viewing live heartbeats can be server side rendered HTML tables or whatever is simplest for you.  A page refresh is perfectly acceptable to view updates of live heartbeats.  We do not expect ajax or websockets to be used.

## Don't Let the Dog Eat Your Homework
Our goal is to understand your thought process, documentation style, and to get a sense of how you reason about a complex system. Please don't spend more than 3-4 hours on this. We'd prefer incomplete work with notes on what you focused on, where you left off, and the limitations of your solution.

If you get stuck or need more information, don't hesitate to reach out for clarity!
