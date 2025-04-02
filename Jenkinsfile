pipeline {
    agent any
    tools {
        nodejs 'nodejs-v18' //Se utiliza la versión 18 de Node JS definida en Jenkins.
    }
    stages {
        stage('Build') {
            steps {
                echo "Ejecutando npm install" 
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo "Ejecutando npm test push" 
                sh 'npm test'
            }
        }
    }
}
