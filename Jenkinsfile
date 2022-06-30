pipeline {
    agent any
    stages {
        stage('Dev AWS') {
            steps {
                withAWS(credentials: 'prod-aws-credentials', region: 'us-east-1') {
                    sh 'aws s3 ls'
                }
            }
        }
    }
}