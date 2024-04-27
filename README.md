### Sample infra cdk aws with lambda

## Pré Requisite

```
Go 1.22
```

## Install Dependencies

### Step 1
```
cd function 
go mod tidy
```

### Step 2

```
cd infra 
go mod tidy
cdk boostrap
cdk deploy
cdk destroy -> to destroy infra
```
## Usage/Sample

```
Outputs:
LambdaGolangProxyAPIDemoMuxStack.apigatewayendpoint = https://w69pfu6yu0.execute-api.us-east-1.amazonaws.com/prod/
curl https://w69pfu6yu0.execute-api.us-east-1.amazonaws.com/prod/app
```