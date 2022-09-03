# hosting full stack application

## about the app
UI Built With Angular 
API Build with Express
Hosted on AWS
_________________________________________________
## the steps that i done
-i cloned the starter code for the project
-modified some Dependencies verisons
-npm i -f
-tested the project locally( worked )
-created database running Postgres check"database.PNG"
-created eb for the back-end
-created s3 for the UI
-edited scripts EX"root package.json,api package.json,frontend package.json, and yml files
-pushed the project to my repo
____________________________________________________
## circle cli process (check"Cli Diagram.png")
- setting the environment variables in circle ci check"env-circle ci.PNG"
- install node 14.15
 - eb/setup
 - aws-cli/setup
 - Install Front-End Dependencies
 - Install API Dependencies
 - Front-End Build
 - Deploy api  (note: i pass the env from circle ci using eb setenv in api package.json)
 - Deploy ui
 check the pipleline successed process "pipeline.PNG"
 _______________________________________________________

 check Elastic Beanstalk "back-end.PNG"
 check s3 bucket "back-end.PNG"
 check overall Diagram process "Diagram.png"

 you can acess the app from: http://udagram-kuro.s3-website-us-east-1.amazonaws.com/
back-end: http://udagramapi-env.eba-priecfvy.us-east-1.elasticbeanstalk.com/
