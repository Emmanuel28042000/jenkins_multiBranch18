node('master') 
{
    stage('Continuous Download_loans_master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans_master') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
