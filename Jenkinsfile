pipeline{
    agent any
    environment{
        name = "Akhil"
        nexuskey = credentials('nexus_creds')
    }
    stages{
        stage('Test'){
        environment{
        name = "AkhilJenkins"
        }
            steps{
                echo "Creds: ${nexuskey}"
                echo "Username: ${nexuskey_USR}"
                echo "Password: ${nexuskey_PSW}"
                echo "name is ${name}"
                echo "$myName and ${myAge}"
            }
        }
    }
}
