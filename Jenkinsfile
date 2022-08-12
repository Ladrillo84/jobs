pipeline {
    
    agent none
   
    stages {
        
        stage("build") {
            agent {docker 'maven:3.8.1-adoptopenjdk-11'}
            steps {
                echo 'building the application'
                sh 'mvn --version'
            }
        }
        
        stage("test") {
            
            steps {
                echo 'testing the application'
            }
        }
        
        stage("deploy") {
            
            steps {
                echo 'Hola mundo'
            }
        }
    }   
}
