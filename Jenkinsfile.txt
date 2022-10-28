pipeline {
    agent any
    stages {
        stage('One') {
            steps {
                echo 'Hi, Welcome tp Pipeline demo....'
            }
        }
        stage('Two') {
            steps {
                echo('Sample testing of stage 2')
            }
        }
        stage('Three') {
            steps {
                echo 'Thanks for using Jenkins Pipeline'
            }
        }
    }
}
