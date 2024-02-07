pipeline {
    agent {
        node ('slave1')
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Hello World'
                sh 'curl google.com'
            }
        }
        stage('Release') {
            steps {
                echo 'Releasing Hello World'
                sh 'curl facebook.com'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Hello World'
                sh 'curl yahoo.com'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Hello World'
                sh 'curl apple.com'
            }
        }  
        stage('Monitor') {
            steps {
                echo 'Monitoring Hello World'
                sh 'curl valtech.com'
            }
        }       
              
    }
}
