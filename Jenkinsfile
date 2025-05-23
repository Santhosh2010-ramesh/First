pipeline{
  agent any 
    stages {
        stage('Clone Code') { 
            steps {
                git 'https://github.com/santhosh2010-ramesh/python-hello-jenkins.git' 
            }
        }
        stage('Run Script') { 
            steps {
                sh 'python3 hello.py' 
            }
        }
      
    }
}
