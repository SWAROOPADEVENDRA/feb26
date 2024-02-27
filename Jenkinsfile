pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git branch: 'main' ,credentialsid: 'your credentials is' ,url: "https://github.com/ramyachetty/maven.git"
              }
       }
      stage('clean')
        {
         steps
            {
             bat "mvn clean"
           }
        }
     stage('compile')
        {
         steps
            {
             bat "mvn compile"
           }
        }
     stage('test')
        {
         steps
            {
             bat "mvn test"
            }
        }
       stage('package')
        {
         steps
            {
             bat "mvn package"
           }
        }
      }
    }
