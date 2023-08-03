pipeline {
    agent { 
        node {
            label 'docker-agent-alpine'
            }
      }
   triggers{ cron('H/2 * * * *') }
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
