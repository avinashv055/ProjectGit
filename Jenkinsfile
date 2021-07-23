pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Im Building code Here'
                sh 'touch f1 f2 f3'
                sh 'ls -l'
                sh 'python --version'

            }
        }
        stage('Test') {
            steps {
                echo 'Im Testing code Here'
                sh 'pwd'
            }
        }
        stage('Scan') {
            steps {
                echo 'Im Scaning code Here'
                sh 'chmod +x *'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Im Deployinh code Here'
                sh 'date'
                sh './code.txt'
            }
        }
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
