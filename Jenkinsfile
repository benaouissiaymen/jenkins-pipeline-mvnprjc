pipeline {
    agent any
tools { 
        maven 'Maven363' 
        jdk 'JDK11' 
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
