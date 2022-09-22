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
			sh mvn clean package
		}
		stage(' deployment ')
		{
			deploy adapters:[tomcat9(url: 'http://172.31.36.158:8080/')]
		}
	}
}

  
       

