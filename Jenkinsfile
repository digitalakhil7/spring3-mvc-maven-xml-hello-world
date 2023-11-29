pipeline{
    agent any
    environment{
        approval = "akhil"
    }
    stages{
        stage('Test'){
            when{
                equals expected: "nikhil", actual: "${approval}"
            }
            steps{
                echo "Hello Master"
            }
        }
    }
}
