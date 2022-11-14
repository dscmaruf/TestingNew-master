node('master') 
{
    stage('Continuous Download Products') 
	{
    git 'https://github.com/dscmaruf/devops1-master.git'
	}
    stage('Continuous Build Products') 
	{
    sh label: '', script: 'mvn package'
	}
	}
