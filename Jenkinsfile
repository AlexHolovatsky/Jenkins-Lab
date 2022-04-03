pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                   sudo yum install python36
                   virtualenv -p python3 test
                   '''
            }
        }
    }
}

