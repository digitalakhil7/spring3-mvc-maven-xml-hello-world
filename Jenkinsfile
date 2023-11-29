pipeline{
    agent any
    environment{
        course = "K8S"
    }
    stages{
        stage('Test'){
        environment{
        name = "AkhilJenkins"
        }
            steps{
                echo "Master Branch Updated"
                echo "Course: ${course} and name is ${name}"
            }
        }
    }
}
