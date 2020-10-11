pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh cd flask-app/
                sh pip install pipenv
                sh pipenv install
            }
        }
        stage('Test') { 
            steps {
                echo 'testing...'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying...'
            }
        }
    }
}