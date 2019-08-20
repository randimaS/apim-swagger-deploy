# wso2-apim-swagger-deployer

Deploys specified swaggers to WSO2 API Manager

### Local Setup

Swagger Deployer requires [WSO2 API Manager](https://wso2.com/api-management/install/) v2.6.0 to run.

- Download and install the deb package for WSO2 API Manager
- To start the WSO2 API Manager 
```sh
$ wso2am-2.6.0
```
- To deploy a specific API
```sh
$ ./gradlew build -Papis="sample-api-v1"
```
- To deploy a set of specific APIs
```sh
$ ./gradlew build -Papis="test-api-v1
test-api-v2"
```
