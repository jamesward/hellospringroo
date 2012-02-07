web: java $JAVA_OPTS -Dspring.profiles.active=prod -jar target/dependency/jetty-runner.jar --port $PORT target/*.war
build-mvn: mvn -DskipTests=true clean prepare-package war:exploded dependency:copy
