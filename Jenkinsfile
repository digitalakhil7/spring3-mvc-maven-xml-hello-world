pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                equals expected: "akhil", actual: "${approval}"
            }
            steps{
                echo "Hello Master"
            }
        }
    }
}
