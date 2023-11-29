pipeline{
    agent any
    environment{
        name = "Akhil"
    }
    stages{
        stage('Test'){
        environment{
        name = "AkhilJenkins"
        }
            steps{
                echo "Master Branch Updated"
                echo "name is ${name}"
                echo "$myName and ${myAge}"
            }
        }
    }
}
