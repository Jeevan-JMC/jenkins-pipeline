pipeline {
    agent any
    stages {
        stage ('firstdev') {
            steps {
                echo "First devops"
            }
        }
        stage ('seconddev') {
            steps {
                echo "second devops"
                sh 'hostname -i'
            }
        }
    }
}
