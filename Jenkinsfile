node {
   stage('GitCheckout') {  
      git 'https://github.com/butuzov/cicd-app'
   }
   stage('MevenCompile') {  
      sh 'mvn compile'
   }
   stage('MevenTest') {  
       sh 'mvn test'
   }
   stage('Maven package') {  
       sh 'mvn package'
   }
   stage('Artifactory') {  
      echo 'hello world'
   }
   stage('Docker Build and Registry') {  
      echo 'hello world'
   }
   stage('Ansible') {  
      echo 'hello world'
   }
}
