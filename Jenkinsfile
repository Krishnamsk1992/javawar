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
                 sh 'mvn install'
            }
            }
            
        }
        stage ('deploy the code ')
        {
            steps
            {
                sh ' cp -R /var/lib/jenkins/workspace/declerative/target/* /opt/apache-tomcat-9.0.8/webapps/ '
            }
            
        }
    }
}
