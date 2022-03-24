pipeline {
    agent any

    stages {
    
        stage('add file') {
            steps {
                sh 'touch MyName3.txt /external'
            }
        }
        
        stage('change the file and paste it') {
            steps {
                sh 'cd /external'
                sh 'echo 'My Name Is Eldar'> MyName3.txt'
                sh 'cat MyName3.txt'
            }
        }
        
        stage('free disk') {
            steps {
                sh 'df -h'
            }
        }
    }
}
