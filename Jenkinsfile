pipeline{
     agent any
     tools {
        maven 'maven'
     }
     stages{
        stage('build'){
         steps{
          sh script: 'mvn clean package'
         }
        }
     }
}
