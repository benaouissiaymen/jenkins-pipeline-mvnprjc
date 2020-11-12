pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('all') {
	    steps {
		bat 'mvn clean package'
	    }
	}
    }
}
