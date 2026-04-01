pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repo...'
            }
        }
        stage('Run Code') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
