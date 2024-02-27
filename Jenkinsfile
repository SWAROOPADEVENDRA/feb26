pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/ramyachetty/maven"
              }
       }
      stage('clean')
        {
         steps
            {
             bat 'mvn clean'
            }
        }
     stage('compile')
        {
         steps
            {
             bat 'mvn compile'
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
