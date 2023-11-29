pipeline{
    agent any
    stages{
        stage('Test'){
            when{
                branch 'master'
            }
            steps{
                echo "Hello Master"
            }
        }
    }
}
