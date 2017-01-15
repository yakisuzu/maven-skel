# mvn generate
`mvn archetype:generate -B -DarchetypeGroupId=pl.org.miki -DarchetypeArtifactId=java8-quickstart-archetype -DarchetypeVersion=1.0.0 -DgroupId=sample -DartifactId=skel-maven`  
`cd skel-maven`  
`mvn versions:use-latest-versions`  
`mvn versions:commit`  
`mvn eclipse:clean eclipse:eclipse`  

# execute
`java -cp target/classes/ sample.App`  

# jar
`mvn package`  
`java -jar target/maven-1.0.0-uber.jar`  

# url
[The Central Repository](http://search.maven.org/)  
