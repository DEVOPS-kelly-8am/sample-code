pipeline {
    agent any
    
    stages {
        stage('Non-Parallel Stage') {
            steps {
                echo 'This stage will be executed first.'
                sleep 5
            }
        }
        //stage ( 'parallel stage') {
        //parallel {
           stage('Branch A') {
              steps {
                  echo "On Branch A"
                  sleep 5
              }
           }
           stage('Branch B') {
              steps {
                 echo "On Branch B"
                 sleep 5
              }
           }
        //}    
       //} 
    }
}
