pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3 --template-body file://template.yml --region 'us-east-1'"
              }
             }
            }
            }
