###Create a new service
###Ref: https://www.serverless.com/framework/docs/providers/aws/cli-reference/create/ ( Use serverless create --template aws-java-gradle --path <name-of-service>)
### HOW-TO USE 
1. git clone <URL>, cd RestService
2. Build 
   ```
   $ gradle wrapper # to build the gradle wrapper jar
   $ ./gradlew build # to build the application jar
   ```
3. Deploy
   ```
   $ sls deploy
   ```
   
4. Usage 
```
$ serverless invoke --function currentTime --log
```
OR ftp
```
$ curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/ping
```
### Call the API
```
$ curl  https://sjuvck8q9d.execute-api.us-west-2.amazonaws.com/test/hello
```

###Create an HTTP API
Reference: https://www.serverless.com/examples/aws-java-simple-http-endpoint/

### Setup AWS Profile (local)
Reference: https://www.google.com/search?q=sls+deploy+--awsprofile&oq=sls+deploy+--awsprofile&aqs=chrome..69i57.5631j0j8&sourceid=chrome&ie=UTF-8

