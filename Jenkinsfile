   node{
     stage('SCM Checkout'){
       git 'https://github.com/madhunivi555/MyTest-5.git' 
     }
     stage('Compile-Package'){
       def mvnHome = tool name: 'maven_3_6_2', type: 'maven'
       sh "${mvnHome}/bin/mvn package"
     }
   }
