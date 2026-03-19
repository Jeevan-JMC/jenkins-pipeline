pipeline {
    agent any
    stages{
        stage('build'){
            steps {
                retry (3){
                    echo "this is for retry example"
                    error "this is error from retry example"
                }
                
            }
        }
    }
}
