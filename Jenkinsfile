pipeline
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
		stage(' build ')
		{
			sh 'mvn clean package'
		}
		
	}
}

  
       

