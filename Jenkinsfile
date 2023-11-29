pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                tag "v1.3"
            }
            steps{
                echo "Tag Present - from Master"
            }
        }
    }
}
