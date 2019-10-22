   pipeline{
      agent any
      stages {
         stage('Build'){
            steps {
             echo "Build The Project"
               bat "mvn clean"
           }
            }
         stage('deploy'){
            steps {
             echo "Deploy The Project"
               bat "mvn compile"
            }   
             }
         stage('Test'){
            steps {
              echo "Test The Project"
               bat "mvn test"
            }
              }
         stage('Delivery'){
            steps {
              echo "Delivery The Project"
               bat "mvn package"
              }   
           }
     }
 } 
      
