## Pipeline process

This app intergrate with CircleCI :

- CircleCI trigger the event when code is changed from github. It will process based on the branch your were setting on Circle CI
- Set up environment
- Preparing environment variable
- Install Nodejs
- Setting up Elastic Beanstalk CLI
- Install AWS CLI
- Configure AWS Acess Key ID
- Checkout code
- Install Front-end Dependences
- Install Back-end Dependences
- Build Front-end app
- Build Back-end app
- Deploy Front-end app to S3
- Deploy Back-end app to Elastic Beanstalk
