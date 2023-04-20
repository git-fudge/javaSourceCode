
# Getting Started with APIMATIC Calculator

## Introduction

Simple calculator API hosted on APIMATIC

## Install the Package

Install the SDK by adding the following dependency in your project's pom.xml file:

```xml
<dependency>
  <groupId>io.github.git-fudge</groupId>
  <artifactId>maven-testing-new</artifactId>
  <version>5.5.106</version>
</dependency>
```

You can also view the package at:
https://mvnrepository.com/artifact/io.github.git-fudge/maven-testing-new/5.5.106

## Test the SDK

The generated code and the server can be tested using automatically generated test cases.
JUnit is used as the testing framework and test runner.

In Eclipse, for running the tests do the following:

1. Select the project APIMATICCalculatorLib from the package explorer.
2. Select `Run -> Run as -> JUnit Test` or use `Alt + Shift + X` followed by `T` to run the Tests.

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| `environment` | Environment | The API environment. <br> **Default: `Environment.PRODUCTION`** |
| `httpClientConfig` | [`ReadonlyHttpClientConfiguration`](doc/http-client-configuration.md) | Http Client Configuration instance. |

The API client can be initialized as follows:

```java
APIMATICCalculatorClient client = new APIMATICCalculatorClient.Builder()
    .httpClientConfig(configBuilder -> configBuilder
            .timeout(0))
    .environment(Environment.PRODUCTION)
    .build();
```

## List of APIs

* [Simple Calculator](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/controllers/simple-calculator.md)

## Classes Documentation

* [Utility Classes](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/utility-classes.md)
* [HttpRequest](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-request.md)
* [HttpResponse](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-response.md)
* [HttpStringResponse](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-string-response.md)
* [HttpContext](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-context.md)
* [HttpBodyRequest](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-body-request.md)
* [HttpCallback Interface](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-callback-interface.md)
* [Headers](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/headers.md)
* [ApiException](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/api-exception.md)
* [Configuration Interface](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/configuration-interface.md)
* [HttpClientConfiguration](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-client-configuration.md)
* [HttpClientConfiguration.Builder](https://github.com/git-fudge/javaSourceCode/blob/5.5.106/doc/http-client-configuration-builder.md)

