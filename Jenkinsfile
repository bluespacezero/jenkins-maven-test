pipeline {
    agent any
    
    tools {
        jdk 'Java'
        maven 'maven-3.6.1'
    }
    
    stages {
        stage('Build') {
            steps {
                echo "print the environment"
                sh "printenv"
            }
        }
    }
}
