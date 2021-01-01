pipeline {
    agent {
        dockerfile {
		args "-v /etc/passwd:/etc/passwd"
		}
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
