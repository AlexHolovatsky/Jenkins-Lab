pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'sudo yum install epel-release -y'
                sh 'sudo yum install nginx -y'
                sh 'sudo systemctl start nginx'
            }
        }
    }
}

