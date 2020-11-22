pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'cd src && go run client.go'
            }
        }
    }
}