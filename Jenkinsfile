pipeline {
    agent {
        lebel 'maven'
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
