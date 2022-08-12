pipeline {
    
    agent {
        label 'aks-default-24169752'
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
                script{
                    sh ''' 
                    velero --help
                    '''
                    }
            }
        }
    }   
}
