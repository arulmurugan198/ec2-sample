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
            sh 'sudo npm install'
            sh 'sudo npm run build'
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
