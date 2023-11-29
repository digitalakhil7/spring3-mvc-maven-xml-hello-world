pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                buildingTag()
            }
            steps{
                echo "Tag Present - from Master"
            }
        }
    }
}
