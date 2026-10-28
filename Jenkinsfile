
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run Python Application') {
            steps {
                bat '"C:\\Users\\vishw\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" hello.py'
            }
        }

        stage('Run Tests') {
            steps {
                bat '"C:\\Users\\vishw\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" -m pytest -v'
            }
        }
    }
}
