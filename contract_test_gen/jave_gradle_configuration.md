To configure the Java gradle project for running Pact tests, please follow the instructions:

Step 1. Add the Following dependencies to `build.gradle` file

```groovy
testImplementation("au.com.dius:pact-jvm-consumer-junit5:4.0.10")
testImplementation("au.com.dius:pact-jvm-provider-junit5:4.0.10")
testImplementation "au.com.dius.pact.provider:junit5:4.2.10"
testImplementation "au.com.dius:pact-jvm-provider-spring:4.0.0"
```

Step 2.  Make sure there's a gradle tasks that runs the generated pact test.
