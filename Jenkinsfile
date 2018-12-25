  node{
   stage('SCM Checkout'){
     
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
    #get the Mvn path
      def mvnHome= tool name: 'maven-3', type: 'maven' 
      sh "${mvnHome}/bin/mvn package"
   }
   
}


