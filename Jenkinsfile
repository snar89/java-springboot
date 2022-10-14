pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn package' 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'mvn test' 
            }

            stage('Test2') {
            steps {
                echo 'Testing..'
                sh 'mvn test' 
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
    }