def gv

pipeline {
    agent any
    
    stages {
        stage("first stage") {
            steps {
                script {
                    gv = load "script.groovy"
                }
                echo 'first stage completed'
            }
        }
        
        stage("second stage") {
            steps {
                script {
                    gv.firstFunction()
                }
            }
        }
    }
    
}
