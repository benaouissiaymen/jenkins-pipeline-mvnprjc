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
				sh 'mvn clean'
			}
		}
    }
}
