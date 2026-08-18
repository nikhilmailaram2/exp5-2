pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python3 -m py_compile addition.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 addition.py'
            }
        }
    }
}
