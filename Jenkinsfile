pipeline
{
    agent any 
    stages
    {
      
         stage ('building the code using maven')
        {
            steps
            {
            withMaven(maven : 'apache-maven-3.6.3')
            {
                 sh 'mvn install'
            }
            }
            
        }
        
    }
}
