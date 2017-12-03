# MavenTest

these command can be combine
	e.g.  mvn clean package

mvn clean   ->  this will download all necessary plug ins, usually this also cleans other.
mvn compile   ->     compile and build
mvn package    ->      package the files to a jar file 
mvn install    ->   Runs the package command and then installs it in your local repo    (users/.m2/repository)
mvn deploy    ->   Runs the package command and then deploys it to a corporate repo   (users/.m2/repository)