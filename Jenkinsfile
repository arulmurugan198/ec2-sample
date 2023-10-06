pipeline {
    agent any

    stages {
        stage('Check') {
        steps {
            sh 'npm --version'
        }
   }
        stage('Build') {
            steps {   
            sh 'npm install'
            sh 'npm run build'
        }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
