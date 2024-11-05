pipeline {
    agent any
	triggers {
		githubPush() 
	}
    stages {
        stage('Build-Java') {
            steps {
                echo 'Build Java Successful !'
            }
        }
        stage('Build-React') {
            steps {
                echo 'Build React Successful !'
            }
        }
    }
}