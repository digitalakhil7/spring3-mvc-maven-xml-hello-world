pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                allOf{
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
