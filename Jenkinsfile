Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.6.9' } }
    stages {
        stage('build') {
            steps {
                python main.py
            }
        }
    }
}