pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                checkout scm

                sh 'python test.py'
                sh '''#!/bin/sh
                
                echo "This is a sample pipeline"
                
                '''
            }
        }
    }
}
