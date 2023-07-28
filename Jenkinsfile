
pipeline {
    agent any
    stages {
        stage('create stack') {
            steps{
                sh 'aws cloudformation create-stack --stack-name myteststack --template-body file://cloudFormation1.json'
            }
        }
    }
}
