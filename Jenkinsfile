pipeline {
    agent {
        dockerfile true
         }

    stages {
        stage('Hello') {
            steps {
                sh 'id'
                sh 'npm version'
                sh 'cdk version'
            }
        }
    }
}
