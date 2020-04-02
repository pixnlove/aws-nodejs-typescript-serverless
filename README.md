## Serverless Starter with NodeJS & Typescript on AWS

Install the [Serverless](https://serverless.com/) framework globally
```
npm install serverless -g
```
Once done, you can run:
```
serverless install -u https://github.com/pixnlove/aws-nodejs-typescript-serverless
```
Install all dependencies with:
```
npm install
```
Try it:
```
sls invoke -f hello
```
And deploy your Lambda on AWS with:
```
sls deploy
```
Use `--stage production` to specify production environment.
