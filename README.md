./gradlew project

./gradlew clean build  web:bootRun -> runs web application
./gradlew clean build  console:bootRun -> runs console application
./gradlew clean build  library:bootRun -> should not be run, because it's only a library

./gradlew clean build bootRun -> Runs web application