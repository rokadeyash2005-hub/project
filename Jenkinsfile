pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/rokadeyash2005-hub/project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building website'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying  Website'
            }
        }

    }
}
