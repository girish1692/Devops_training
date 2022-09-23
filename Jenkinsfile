pipeline
{	
	agent any 
		stages
		{
			stage('continuous download')
			{
				steps
				{
					git 'https://github.com/pavanoltraining/JenkinsPipelineDemoProject.git'
				}			
			}	
			stage(' build ')
			{
				steps
				{
					sh 'mvn -f JenkinsPipelineDemoProject/pom.xml clean package'
				}	
			}
		}
}


  
       

