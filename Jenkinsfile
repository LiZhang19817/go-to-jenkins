pipeline {
    agent any
    tools {
        go 'go-1.12'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
       stage('Post'){
            steps{
               sh 'uptime'
            }
          }
        }
    }
}
