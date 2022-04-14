properties([pipelineTriggers([pollSCM('H * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'python3 main.py'
            }
        }
    }
}
