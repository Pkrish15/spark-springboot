# spring-spark-example
An example of setting up Spring-Boot with Spark with simple word count application
1) It can be run either in IDE or an maven application. <br>
2) $ spark-springboot> mvn clean install package -e -DskipTests=true <br>
3) If you don't want to skip the tests exclude -DskipTests=true in above step 2. <br>
4) $ spark-springboot/target> java -jar spark-springboot.jar <br>
5) Else in shot you can call $ spark-springboot> mvn clean install spring-boot:run -e <br>
6) You can hit http://localhost:8080/api/wordcount to view the output. <br>
7) You can also visualize your spark-jobs execution using http://localhost:4040/ <br>
