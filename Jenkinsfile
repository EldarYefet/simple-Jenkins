pipeline {
    agent any

    stages {
    
        stage('add file') {
            steps {
                sh 'touch MyName3.txt /external'
                sh 'cd /external'
                sh 'ls -l'
                sh 'echo "My Name Is Eldar"> MyName3.txt'
                sh 'cat MyName3.txt'
                sh 'df -h'
            }
        }
    }
}
