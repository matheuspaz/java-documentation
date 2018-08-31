# Creating your first spring application using spring boot

# Topics
* [Install Java Development Kit (JDK) in your operation system](#)
* [Creating your application with Spring Initializr](#creating-your-application-with-spring-initializr)
* [Building and fix common build errors](#building-and-fix-common-build-errors)
* [Running application with live reload](#running-application-with-live-reload)

# Creating your application with Spring Initializr
After we install the [Java Development Kit](#), let's go to create your spring application with spring initializr.

First, access [Spring Initializr web site](https://start.spring.io/). After access the site, follow the steps:
* In generate field, set __Gradle__ with __Java__ and __Spring Boot__ in version __2.0.4__.
* In __Project Metadata__ set __Group__ with domain of your company and __Artifact__ with your project name.
* In __Dependencies__ in search field, add the [__Web__, __Thymeleaf__, __JPA__, __Devtools__, __MySQL__] dependencies.
* Click in __Generate Project__ button (or use shortcut key __alt + enter__) and download the zip.

# Building and fix the common build errors
After download the zip. Extract in your preferred folder.
After extracted, access main folder and run:
```
gradle booRun
```


