pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Hello W orld'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('continue') {
            
            input {
                
                message "Should we continue y/n"
                ok "yes we should continue"
            }
            steps {
                echo 'Hello World'
            }
        }
        stage('deploy to prod') {
            steps {
                echo 'Hello World'
            }
        }

    }
            post { 
            always { 
                echo 'I will always say Hello again!'
            }
            failure {
                
                echo "i am failure"
            }
            success {
                echo "i am success"
            }
            aborted {
                echo "i am aborted"
            }
        }
}
