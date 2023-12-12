pipeline {
    agent any
    stages {
        stage('Lint Checks'){
            steps {
                sh "echo ***** Starting Style Checks *****"
                // sh "pip3 install pylint"
                // sh "pytlint *.py || true"
                sh "echo ***** Style Checks Are Completed *****"
            }
        }
        stage('Static Code Analysis') {
            steps {
                sh "echo Starting Static Code Analysis"
            }
        }
    }
}

