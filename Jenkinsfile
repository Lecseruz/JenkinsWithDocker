pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'docker build -t example .'
		sh 'docker image save -o example.zip example'	
            }
        }
    }
}
