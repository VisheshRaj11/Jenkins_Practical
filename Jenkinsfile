pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/VisheshRaj11/Jenkins_Practical.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Portfolio Website...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment Successful 🚀'
            }
        }
    }
}
