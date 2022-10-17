pipeline
{
    agent any 
    stages
    {
      
         stage ('building the code using maven')
        {
            steps
            {
            withMaven
            {
                 sh 'mvn install'
            }
            }
            
        }
        
    }
}
