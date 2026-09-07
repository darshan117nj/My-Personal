pipeline{
    agent any

    stages{
        stage('Host name'){
            step{
                sh 'hostname'
            }
        }
        stage('Memory Usage'){
            step{
                sh 'free -h'
            }
        }

        stage('Disk usage'){
            step{
                sh 'df -h'
            }
        }

        stage('CPU details'){
            step{
                sh 'lscpu'
            }
        }
    }
}
