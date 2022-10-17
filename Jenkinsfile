pipeline
{
    agent any 
    tools {
        maven 'Maven_3.5.2' 
    }
    stages
    {
      
         stage ('building the code using maven')
        {
            steps
            {
            sh 'mvn clean install'
            }
            
            
        }
       
    }
}
