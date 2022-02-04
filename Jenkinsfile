node{
// demo
   stage('SCM Checkout'){
     git 'https://github.com/sharmauma/sonarepo'
   }
   stage('Compile-Package'){
      // Get maven home path
      //def mvnHome =  tool name: 'maven-3', type: 'maven'   
       sh "mvn package"
    
   }
   }
   
