pipeline {
    
    agent any
    
    stages {
        
         stage('Initialize'){
            def dockerHome = 'myDocker'
            env.PATH = "${dockerHome}/bin:${env.PATH}"
        }
        
        stage("build") {
           steps {
                echo 'testing the application'
            }
        }
        
        stage("test") {
            
            steps {
                echo 'testing the application'
            }
        }
        
        stage("deploy") {
            
            steps {
                sh 'docker --version'
            }
        }
    }   
}
