https://docs.aws.amazon.com/zh_cn/lambda/latest/dg/nodejs-package.html

```shell
zip -r datagen-cognito-setup-2022.zip .
```

```shell
aws lambda update-function-code --function-name kinesis-data-generator-cognito-setup --zip-file fileb://datagen-cognito-setup-2022.zip
```