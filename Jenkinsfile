pipeline {
    agent { 
        node {
            label 'docker-agent-maven'
            }
      }
    stages {
        stage('Build') {
            steps {
                sh 'javac Test.java'
            }
        }
        stage('Test') {
            steps {
                sh 'java Test'
            }
        }
        stage('Deliver') { 
            steps {
                echo 'PipeLine completed successfully!'
            }
        }
    }
}
