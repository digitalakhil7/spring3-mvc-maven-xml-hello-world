pipeline{
    agent any
    stages{
        stage('Test'){
            when{
                expression { BRANCH_NAME ==~ /(prod|test)/ }
            }
            steps{
                echo "Hello Akhil"
            }
        }
    }
}
