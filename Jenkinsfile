pipeline{
  agent any 
    stages {
        stage('Clone Code') { 
            steps {
                git credentialsId: 'githubpat', url: 'https://github.com/Santhosh2010-ramesh/First.git'
            }
        }
        stage('Run Script') { 
            steps {
                sh 'python3 hello.py' 
            }
        }
      
    }
}
