def gv

pipeline {
    agent any
    
    stages {
        stage("first stage") {
            steps {
                script {
                    gv = load
                }
                echo 'first stage completed'
            }
        }
    }
    
}
