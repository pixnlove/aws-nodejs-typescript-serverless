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
Deploy your Lambda on AWS with:
```
sls deploy
```
And try to invoke your lambda (located in `handler.ts`):
```
sls invoke -f hello
```
Use `--stage production` to specify production environment.

Remove your Lambda from AWS with:
```
sls remove
```
