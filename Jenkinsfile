pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                   yum install epel-release
                   yum install nginx
                   systemctl start nginx
                   '''
            }
        }
    }
}

