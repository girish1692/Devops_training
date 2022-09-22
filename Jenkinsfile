pipeline
{	
	agent any
	{ 
		stages
		{
			stage('continuous download')
			{
				steps
				{
					git 'https://github.com/spy16/droplets.git'
				}			
			}	
			stage(' build ')
			{
				steps
				{
					sh 'mvn clean package'
				}	
			}
		}
	}
}

  
       

