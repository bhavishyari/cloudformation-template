pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name demo-ecs --template-body file://democft.yml --region 'us-east-2' --parameters ParameterKey=asgNotificationEp,ParameterValue=bhavishya@rapidinnovation.dev ParameterKey=keyName,ParameterValue=fromJenkinstoAWS --capabilities CAPABILITY_IAM"
              }
             }
            }
            }