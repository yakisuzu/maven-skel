# mvn generate
`mvn archetype:generate -B -DarchetypeGroupId=pl.org.miki -DarchetypeArtifactId=java8-quickstart-archetype -DarchetypeVersion=1.0.0 -DgroupId=sample -DartifactId=maven-skel`  
`cd maven-skel`  
`mvn versions:use-latest-versions`  
`mvn versions:commit`  
`mvn eclipse:clean eclipse:eclipse`  

# execute
`java -cp target/classes/ sample.App`  

# jar
`mvn package`  
`java -jar target/maven-skel-1.0.0-jar-with-dependencies.jar`  

# url
[The Central Repository](http://search.maven.org/)  
