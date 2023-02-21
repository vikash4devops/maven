pipeline{
     agent any
     tools {
        maven 'maven'
          }
     steges{
        stege('build'){
        steps{
          sh 'mvn clean package'
         }
        }
     }
}
