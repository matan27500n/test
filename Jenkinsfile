pipeline {
    agent { docker { image 'python_with_pytest:latest' } }
    // agent any
    stages {
        stage('test') {
            steps {
                //sh 'PYTHONPATH=. pytest'
                sh 'python -m pytest tests'
            }
        }
        stage('test2') {
            steps {
                echo "Hello World3"   
            }
        }
    }
}
