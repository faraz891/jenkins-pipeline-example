pipeline {
    agent any 
    options { timestamps () }

    stages {
        stage('Teste') {
            steps {
                renewAutoScalingGroup("teste", "us-east-1")          
            }
        }
    }
}