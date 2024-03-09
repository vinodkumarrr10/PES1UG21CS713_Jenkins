pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build 'PES1UG21CS713_1'
                sh 'g++ main.cpp -o output'
                
            }
        }
        stage('Test') {
            steps {
                sh './outpu'
                
            }

        }
        stage('Deploy') {
            steps {
                
               
                echo 'Deploy'
                
            }
        }
    }
    
    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
