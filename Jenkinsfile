pipeline{
  agent any
  stages{
    stage("mystage"){
      steps{
            dir ("my_dir"){
              git url : "https://github.com/ganesh770924/github-basics.git" , branch : "master"
            }
        stage('Shell script'){
          steps {
            sh "cat README.md"
          }
           }        
          }
         }
        }  
