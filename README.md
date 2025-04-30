# Simplest example of a Gradle project using the Lydtech Component Test Framework

See https://github.com/lydtechconsulting/component-test-framework/blob/main/README.md#using-gradle for the steps involved in setting this up

## Building

```
./gradlew clean build; docker build -t samples/my-maven-app .
```

## Running Component Tests
```
./gradlew clean componentTest
```
