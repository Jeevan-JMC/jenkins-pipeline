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
    
        stage('build'){
            steps {
                script {
                    def course ="k8s"
                    if(course == "k8s")
                    println("Welcome to ${course} k8s")
                    else
                    println("Do not have ${course}")
                }
                
            }
        } 
    }
}   
