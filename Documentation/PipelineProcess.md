# Pipeline-Process
- We make a change in the project.
- Then we commit and push the change to the github repository.
- Then CircleCI starts working and running scripts according to the config.yml in the .circleci folder to build the api and frontend.
- CircleCI waits for approval.
- CircleCI starts to deploy both the api and the frontend.
- The updates reaches AWS and is applied.
- The updates is live and available for users.
