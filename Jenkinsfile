pipeline
agent any
{ 
	stages
	{
		stage('continuous download')
		{
			steps
			{
				git 'https://github.com/girish1692/Devops_training.git'
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

  
       

