## Creating Jobs in Jenkins
- Log into the jenkins webserver at http://35.176.10.123:8080/
- Create a New Item
- Name it and select "Freestyle Project"
- Tick discard old builds and set max number of builds to 3
- At the bottom in the build section select "Execute shell" and type something like `pwd` to test if it is working
- In the Post-build Actions you can select another job you have created so that it runs at the end of this job's execution.
- Click Save
