
pipeline {
    
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
               sh  'npm install'
               sh 'npm build'
 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
