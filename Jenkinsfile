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
        stage("deploy") {   
            steps {
                sh 'docker --version'
            }
        }
    }   
}
