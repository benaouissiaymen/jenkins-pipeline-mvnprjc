pipeline {
    agent any
tools { 
        maven 'Maven 3.6.3' 
        jdk 'jdk11' 
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('all') {
	    steps {
		sh 'mvn clean'
	    }
	}
    }
}
