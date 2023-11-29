pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                anyOf{
                    branch 'master'
                    environment name: 'approval', value: 'akhilvee'
                }
            }
            steps{
                echo "Hello Master"
            }
        }
    }
}
