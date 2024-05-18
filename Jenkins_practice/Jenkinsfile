pipeline {
    agent {
        docker {image 'node:16-alpine' }
    }
    stages {
        stage ('check_version') {
            steps {
                sh 'node --version'
            }
        }
    }
    
}
