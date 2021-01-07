pipeline{
agent any
stages {
Stage("clean") {
steps{
		sh "mvn clean"
	       }
	}
Stage("test") {
steps{
		sh "mvn test"
	      }
}
Stage ("package") {
steps{
		   sh "mvn package"
		}
	}
}