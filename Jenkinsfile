pipeline {
    agent {
        docker {
            image 'maven:3-alpine'    
        }
    }
    stages {
        stage('Build') {
            steps {
                sh '''
                  pwd
                  ls -l
                  cat f
                  cat g
                  
                  mvn --version
                '''
            }
        }
    }
}
