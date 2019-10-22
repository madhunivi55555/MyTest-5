   pipeline{
      agent any
      stages {
         stage('Build'){
            steps {
             echo "Build The Project"
               sh "mvn clean"
           }
            }
         stage('deploy'){
            steps {
             echo "Deploy The Project"
               sh "mvn compile"
            }   
             }
         stage('Test'){
            steps {
              echo "Test The Project"
               sh "mvn test"
            }
              }
         stage('Delivery'){
            steps {
              echo "Delivery The Project"
               sh "mvn package"
              }   
           }
     }
 } 
      
