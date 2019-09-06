node{
    
  stage('clone') {
    git 'https://github.com/vtvc/mahalogin.git'
  }
  
   stage('maven targets') {
    sh label: '', script: 'mvn install'
   }
    
    
}
