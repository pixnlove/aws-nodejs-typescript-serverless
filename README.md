# Serverless Starter with NodeJS & Typescript on AWS
For a quick start, clone this project:
```
git clone https://github.com/pixnlove/aws-nodejs-typescript-serverless
```
Install all dependencies with:
```
npm install
```
After, you need to install the [Serverless](https://serverless.com/) framework globally
```
npm install serverless -g
```
Add your AWS Credentials to Serverless:
```
aws configure
```
Try to invoke your lambda (`handler.ts`):
```
sls invoke -f hello
```
And deploy your Lambda on AWS with:
```
sls deploy
```
Use `--stage production` to specify production environment.

Remove your Lambda from AWS with:
```
sls remove
```
