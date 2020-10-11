pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                bat 'cd flask-app/'
                bat 'pip install pipenv'
                bat 'pipenv install'
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