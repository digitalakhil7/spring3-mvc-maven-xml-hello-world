pipeline{
    agent any
    environment{
        course = "k9"
    }
    stages{
        stage('Test'){
            when{
                environment name: 'course', value: 'k8'
            }
            steps{
                echo "Hello Akhil"
            }
        }
    }
}
