# third-demo-ear
##Generating EAR project -Use below command

`mvn archetype:generate -DgroupId=com.drilldevops -DartifactId=demo-ear -Dversion=1.0.0-SNAPSHOT -Dpackage=com.drilldevops -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`

###In the file « pom.xml », change the « packaging » value to « ear » (if the packaging element is missing, add a new one)
`<packaging>ear</packaging>`
