pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                 echo 'Built'
                
            }
        }
 stage('Test') {
            steps {
                echo 'Tested' 
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deployed' 
            }
        }
    }
    post{
        always{
            echo 'Sucess or failure'
        }
        Sucess{
            echo 'failure'
        }
        failure{
            echo 'failure'
        }
    }
}
