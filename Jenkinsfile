pipeline {
    agent none 
    stages {
        stage('Build') {
           
            steps {
                echo 'Hello, Maven'
                bat 'mvn --version'
            }
        }
        stage('Test') {
            
            steps {
                echo 'Hello, JDK'
                bat 'java -version'
            }
        }
    }
}
