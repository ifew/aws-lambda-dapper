# Example AWS Lambda C# .NET Core 2.2 with connect MySQL via Dapper

## Test and Deploy with AWS CLI

**Deploy**
```
$ cd src/aws-lambda-dapper
$ dotnet lambda deploy-function {LAMBDA_FUNCTION_NAME} –-function-role {ROLE_NAME}
```

**Try to Run and Get result**
```
$ cd src/aws-lambda-dapper
$ aws lambda invoke --function-name {LAMBDA_FUNCTION_NAME} output.txt
```