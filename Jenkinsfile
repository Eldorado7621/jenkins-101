pipeline {
    agent { 
        node {
            label 'jenkins_agent'
            }
      }
   
    stages {
        stage('Build') {
            steps {
                echo "Biiuilding..."
               
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
               
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
