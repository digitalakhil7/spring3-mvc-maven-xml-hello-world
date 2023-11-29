pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
               tag pattern: "v\\d{1,2}.\\d{1,2}.\\d{1,2}", comparator: "REGEXP"
            }
            steps{
                echo "Tag Present - from Master"
            }
        }
    }
}
