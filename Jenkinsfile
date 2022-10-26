pipeline
{
    agent any 
    stages
    {
      
         stage ('building the code using maven')
        {
            steps
            {
            withMaven(maven : 'Maven_Home')
            {
                 sh 'mvn clean install'
            }
            }
        }   
            
        stage ('deploy the code ')
            
        }
    }
}
