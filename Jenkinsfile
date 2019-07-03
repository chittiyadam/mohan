node{
  stage('SCM CHECKOUT'){
    git 'https://github.com/chittiyadam/mohan'
   }
  stage('clean-pacakge'){
    sh 'mvn clean'
    sh 'mvn package'
  }
 }
