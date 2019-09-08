node{
    
  stage('clone') {
    git 'https://github.com/vtvc/mahalogin.git'
  }
  
   stage('maven targets') {
    bat label: '', script: 'mvn install'
   }
    
    
}
