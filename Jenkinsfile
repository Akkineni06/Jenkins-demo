pipeline {

    agent any

    stages {
        stage('Make Folders and files') {
            steps {
                bat '''
                mkdir testingPipleline
                '''
            }
        }
        stage('View') {
            steps {
                bat '''
                dir
                '''
            }
        }
        stage('Run') {
            steps {
                bat 'script.bat'
            }
        }
    }
}