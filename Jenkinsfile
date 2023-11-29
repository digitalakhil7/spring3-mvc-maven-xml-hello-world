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
                    environment name: 'approval', value: 'akhil'
                }
            }
            steps{
                echo "Hello Master"
            }
        }
    }
}
