pipeline {
    agent any

    stages {
    
        stage('add file') {
            steps {
                sh 'touch MyName3.txt /external'
            }
        }
        
        stage('change the file ) {
            steps {
                sh 'cd /external'
            }
        }
        
        stage('paste it') {
            steps {
                sh 'echo 'My Name Is Eldar'> MyName3.txt'
            }
        }
        
        stage('free disk') {
            steps {
                sh 'df -h'
            }
        }
    }
}
