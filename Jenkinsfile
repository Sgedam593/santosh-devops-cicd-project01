pipeline {

    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Welcome Santosh'
            }
        }

        stage('Docker Version') {
            steps {
                sh 'docker --version'
            }
        }

        stage('Current Directory') {
            steps {
                sh 'pwd'
            }
        }
        stage('List Files') {
            steps {
               sh 'ls -la'
            }
        }

        stage('Docker Images') {
             steps {
               sh 'docker images'
            }
        }

    }

}
