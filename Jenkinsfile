pipeline {
    
    agent {
        label 'velero'
    }
   
    stages {
        
        stage("build") {
            
            steps {
                echo 'building the application'
            }
        }
        
        stage("test") {
            
            steps {
                echo 'testing the application'
            }
        }
        
        stage("deploy") {
            
            steps {
                sh 'velero --help'
            }
        }
    }   
}
