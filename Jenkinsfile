
pipeline {
    

    
    agent any 
    stages {
        stage('build') {
            steps {
                 echo 'Building..'
                sh 'node --version'
 
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
