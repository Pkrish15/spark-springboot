# spring-spark-example
An example of setting up Spring-Boot with Spark with simple word count application
1) It can be run either in IDE or an maven application. <br>
2) $ spark-springboot> mvn clean install package -e -DskipTests=true <br>
3) $ spark-springboot/target> java -jar spark-springboot.jar <br>
4) You can hit http://localhost:8080/api/wordcount to view the output. <br>
5) You can also visualize your spark-jobs execution using http://localhost:4040/ <br>
