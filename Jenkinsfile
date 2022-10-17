pipeline
{
    agent any 
    tools {
        maven 'Maven_3.6.3' 
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
