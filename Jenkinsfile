node('master') 
{
    stage('Continuous Download Master') 
	{
    git 'https://github.com/dscmaruf/devops1-master.git'
	}
    stage('Continuous Build Master') 
	{
    sh label: '', script: 'mvn package'
	}
	}
