###Create a new service
###Ref: https://www.serverless.com/framework/docs/providers/aws/cli-reference/create/ ( Use serverless create --template aws-java-gradle --path <name-of-service>)
### HOW-TO USE 
1. git clone https://github.com/arpijoy/RestService.git 
2. $ cd RestService
3. Build 
   ```
   $ gradle wrapper # to build the gradle wrapper jar
   $ ./gradlew build # to build the application jar
   ```
4. Deploy
   ```
   $ sls deploy
   ```
   
5. Usage 
```
$ serverless invoke --function currentTime --log
```
OR ftp
```
$ curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/ping
```

###Create an HTTP API
Reference: https://www.serverless.com/examples/aws-java-simple-http-endpoint/

### Setup AWS Profile (local)
Reference: https://www.google.com/search?q=sls+deploy+--awsprofile&oq=sls+deploy+--awsprofile&aqs=chrome..69i57.5631j0j8&sourceid=chrome&ie=UTF-8

