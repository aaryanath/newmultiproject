node('master_lab') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous bBuild') 
	{
    sh 'mvn package'
	}
}
