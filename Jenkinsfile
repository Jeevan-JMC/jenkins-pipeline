pipeline {
    agent any
    stages {
         stage('first'){
             agent {label 'app-slave'}
          steps {
                echo "Hello first"
                sh 'hostname -i'
            }
        }
    
        stage('second'){
            steps {
                echo "Hello second"
                sh 'hostname -i'
                }
                
            }
        } 
    }
}   
