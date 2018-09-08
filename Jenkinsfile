pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Git Clone'){
            steps{
                git 'https://github.com/gosyoin/hello-world.git'
            }
        }
    }
}

