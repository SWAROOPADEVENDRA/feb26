pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/SWAROOPADEVENDRA/feb26.git"
              }
       }
      stage('run')
        {
         steps
            {
             bat "javac demo.java"
             bat "java demo.java"
            }
        }
       
      }
    }
