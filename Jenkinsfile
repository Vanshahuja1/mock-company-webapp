pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // TODO: Build the project
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // TODO: Test the project
                sh './gradlew test'
            }
        }
    }
}
