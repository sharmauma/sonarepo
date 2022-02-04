pipeline{
    agent any
    tools {
      maven 'maven'
    }
    
    stages{
        stage('SCM'){
            steps{
                git credentialsId: 'github', 
                    url: 'https://github.com/sharmauma/sonarepo'
            }
        }
        
        stage('Maven Build'){
            steps{
                sh "mvn clean package"
            }
        }
    }
}
