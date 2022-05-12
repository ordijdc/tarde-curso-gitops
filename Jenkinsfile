pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
		  
	  stage('Efimero') {
		agent { label 'docker-agent' }
            steps {
                ls -ltr /
            }
        }
    }
   
}
