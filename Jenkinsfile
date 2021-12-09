pipeline{
  agent any
  stages{
    stage("mystage"){
          steps{
            cat README.md
            dir ("my_dir"){
              git url : "https://github.com/ganesh770924/github-basics.git" , branch : "master"
            }
           }        
          }
         }
        }  
