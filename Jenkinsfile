pipeline {
    
    agent any
    
    stages {
        
         stage('Initialize') {
            def dockerHome = 'c:/Program Files/Docker/cli-plugins'
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
