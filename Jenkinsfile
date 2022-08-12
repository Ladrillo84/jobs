pipeline {
    agent any
    stages {
        stage("Initialize") {
           steps {
               script {
                    def dockerHome = tool 'myDocker'
                    env.PATH = "${dockerHome}/bin:${env.PATH}"
               }
           }
        }
        stage("build") {   
            steps {
                sh 'docker --version'
            }
        }
        stage("deploy") {   
            steps {
                echo '$AZURE_BACKUP_RESOURCE_GROUP'
            }
        }
    }   
}
