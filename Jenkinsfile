<<<<<<< HEAD
node {
	stage('preparation') {
	    checkout scm
	}
	stage('build') {
        /home/edureka/maven/bin/mvn clean install 
	}
=======
pipeline {
    agent any
    stages {
        stage ('checkout') {
            steps {
		checkout scm
            }
        }
        stage ('Build') {
            steps {
                sh '${m2_home}/bin/mvn -f java-sample-app/pom.xml clean install' 
            }
        }
    }
>>>>>>> 5dc877b01ece554b5ed33fb5762c3d068bedf818
}
