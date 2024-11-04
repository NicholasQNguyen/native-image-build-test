# Explanation

This project can be run by setting your java home to a GraalVM JDK.

`./gradlew clean nativeRun` is all that's needed to perform the graalvm test

JDK tests can be run using `./gradlew clean compileJava` and `./gradlew clean bootRun`

| System           | JDK Compile Time | JDK Startup Time | Native Compile Time | Native Startup Time |
|------------------|------------------|------------------|---------------------|---------------------|
| 2019 Macbook Pro |                  |                  |                     |                     |
| M1 Pro xxxxx     |                  |                  |                     |                     |
| M3 Pro 12c 36GB  | 650ms            | 1.49s            | 82s                 | 20.5ms              |
| M3 Max xxxxx     |                  |                  |                     |                     |