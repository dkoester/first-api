# first-api
A quick demo-able app using mulesoft running locally to say hi!

I used the built in naming convention so this handler will need edited.
http://localhost:8081/greeting

## TO RUN LOCALLY
1. Clone this repo
2. Import the project into mulesoft
3. Make sure the package Explorer shows the project
4. Right click on the project -> Run As -> Mule Application
5. Boom, you have a running API with a single GET endpoint

## API SWAGGER - yaml
1. This is the swagger.yaml file in the root of the project.
2. To view this spec, copy this file into [here](http://editor.swagger.io/)
3. For now this swagger is more of an example template.

### External API
1. Required to have the second external endpoint returning. Make an api to return something at `localhost:5000/examples`
2. A Python/Flask API was built an is under my repo 
