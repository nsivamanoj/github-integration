pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running JUnit and Selenium tests'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Running SonarQube code analysis'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Postman integration tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production server'
            }
        }
    }
}