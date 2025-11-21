pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo "build"
            }
        }
        stage('Test'){
            steps {
                echo "Test"
                junit 'reports/**/*.xml'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy" //
            }
        }
    }
}
