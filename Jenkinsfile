pipeline {
    agent any
    stages {
        stage('Dev-AWS') {
            steps {              
                withCredentials([<object of type com.cloudbees.jenkins.plugins.awscredentials.AmazonWebServicesCredentialsBinding>]){
                sh 'aws s3 ls'
            }
            }
        }
    }
}
