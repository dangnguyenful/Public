pipeline {
    agent {
        node {
            label 'java-slave' 
        }
    }
    stages {
        stage('Build-Java') {
            steps {
                sh './mvnw package' 
            }
        }
        stage('Build-React') {
            steps {
                sh './mvnw package' 
            }
        }
    }
}