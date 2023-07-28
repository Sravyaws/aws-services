pipeline {
    agent any
    stages {
        stage("create stack") {
            sh "aws cloudformation create-stack --stack-name myteststack --template-body file://cloudFormation1.json --region ap-south-1
        }
    }
}
