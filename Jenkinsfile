pipeline {
    agent any

    stages {
    
        stage('add file') {
            steps {
                sh { 
                 'touch MyName3.txt /external'
                 'cd /external'
                 'echo "My Name Is Eldar"> MyName3.txt'
                 'df -h'
                }
            }
        }
    }
}
