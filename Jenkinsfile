pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build using Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Run tests with JUnit/TestNG'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code analysis with SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security scan with OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to AWS EC2 (staging)'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Run integration tests with Selenium on staging'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to AWS EC2 (production)'
            }
        }
    }
}
