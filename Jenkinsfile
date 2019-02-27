pipeline {
    agent any 
    stages {
        stage('Build') {
           
            steps {
                echo 'Hello, Maven'
                bat 'mvn --version'
                
                //below commad for linux 
                // sh 'mvn --version' 
                
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
