offline-todos
============================

Improved version of the Todos boilerplate example.  Includes:

- offline mode via Ground.Collection
- responsive design to support tablet rotation  
- selenium/nightwatch acceptance tests  
- migrating towards a workflow-centric MVC pattern

============================
#### Meteor Version

1.0.3.1


============================
#### Installation

````sh
# Should be as simple as cloning the repository...  
git clone https://github.com/awatson1978/offline-todos.git

# And then running it...
cd offline-todos
meteor
````


============================
#### Run Acceptance Tests

````sh

# optional:  you may want to reset your application data
terminal-a$ meteor reset

# run your application as usual
terminal-a$ meteor

# then open up a second terminal and run_nightwatch to run all tests
terminal-b$ chmod 777 run_nightwatch.sh
terminal-b$ ./run_nightwatch.sh

# or specify a specific test
terminal-b$ ./run_nightwatch.sh -t tests/homePage.js

````
