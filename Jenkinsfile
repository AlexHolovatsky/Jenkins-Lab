pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                    sudo yum install epel-release -y
                    sudo yum install nginx -y
                    sudo systemctl start nginx
                '''
            }
        }
    }
}

