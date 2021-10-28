pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'checkout'
            }
        }
        stage('Docker_Buid') {
            steps {
                echo 'Building'
            }
        }
        stage('Approval') {
            steps {
                echo 'approval'
            }
        }
        stage('Docker push') {
            steps {
                echo 'pushing image'
            }
        }
    }
}
