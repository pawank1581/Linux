pipeline {
    agent any
    stages {
        stage('Monitoring') {
            steps {
                sh '''
                    echo "File System Monitoring"
                    df -h
                   '''
            }
        }
        stage('Monitoring_More') {
            steps {  
                sh '''
                    echo "Memory"
                    free -m
                '''
            }
        }
    }
}
