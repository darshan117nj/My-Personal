pipeline {
    agent any

    stages {
        stage('Host name') {
            steps {
                sh 'hostname'
            }
        }

        stage('Memory Usage') {
            steps {
                sh 'free -h'
            }
        }

        stage('Disk usage') {
            steps {
                sh 'df -h'
            }
        }

        stage('CPU details') {
            steps {
                sh 'lscpu'
            }
        }
    }
}

