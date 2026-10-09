pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ranjanaramesh109-art/DemoPythonProject.git'
            }
        }

        stage('Run Python Program') {
            steps {
                sh 'python3 --version'
                sh 'echo 12 | python3 main.py'
            }
        }
    }
}
