pipeline {
    agent any
    
    tools {
        maven 'maven-3.6.1'
    }
    
    stages {
        stage('Build') {
            steps {
                sh "mvn clean package spring-boot:repackage"
                sh "printenv"
            }
        }
    }
}
