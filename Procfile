web: java $JAVA_OPTS -Dspring.profiles.active=prod -jar target/dependency/jetty-runner.jar --port $PORT target/*.war
build-mvn: mvn clean war:exploded dependency:copy
