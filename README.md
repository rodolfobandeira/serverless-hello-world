# serverless-hello-world
Playground to study serverless framework

Content based on Serverless and GraphQL course from:

[https://acloud.guru/course/serverless-with-graphql/](https://acloud.guru/course/serverless-with-graphql/)

#### 1. Clone this repository:

`git clone https://github.com/rodolfobandeira/serverless-hello-world`

`cd serverless-hello-world`

#### 2. Deploy the code to AWS. (You must have AWS Cli working. Also nodejs 4.3 and serveless framework installed)

`serverless deploy`

#### 3. Call the hello function we have inside handler.js

`serverless invoke --function hello --data 'To the cloud!' --log`

```
{
    "message": "Hi, this function worked!"
}
```

Along reporting log details, you should see a nice stats line showing something like this:

```
Duration: 0.56 ms
Billed Duration: 100 ms
Memory Size: 1024 MB
Max Memory Used: 24 MB
```
