pipeline {
    agent any

    stages {
        stage('Hello-A') {
            steps {
                echo 'Hello World-A'
            }
        }
        stage('Run Linux command') {
            steps {
                sh 'date'
            }
        }
        stage('print msg') {
            steps {
                echo 'My pipeline works'
            }
        }
    }
}
