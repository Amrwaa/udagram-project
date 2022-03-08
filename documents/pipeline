

## GitHub
Developers commit and push the code to the GitHub repository which is linked to the CircleCI platform. GitHub triggers the CircleCI platform when code is pushed to the repository.

## CircleCI
CircleCI reads the .circleci/config.yml file which tells the service what has to be done. In this case 2 jobs has to be run by CircleCI whisch is
- Backend job
- Frontend job

Backend: Runs the build script, exports all environment variables from CircleCI configuration to a .env file, then runs the archive script. Then uses AWS CLI to upload archive to S3.               
Frontend: Runs the build script given in the package.json file. Then uses AWS CLI to upload assets to S3 bucket.
