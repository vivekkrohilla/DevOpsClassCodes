#!/usr/bin/env groovy
pipeline {
    agent {
        label 'newnode'
    }
    stages {
        stage('Stage 1') {
            steps {
                git 'https://github.com/vivekkrohilla/DevOpsClassCodes.git' 
            }
        }
    
        stage('Stage 2') {
            steps {
                sh 'mvn clean install package' 
            }
        }
    }
}
