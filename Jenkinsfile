Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.6.9' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World"'
		sh '''
		   echo "Multiline shell steps works too"
		   ls -lah
		'''
            }
        }
    }
}