pipeline {
 agent any
    tools
    {
        nodejs 'npm'
    }
    environment{
        Name= "Rutvik"
}
    stages {
        stage('Clone') {
            steps {
            git branch: 'main', url: 'https://github.com/runilasawant/jenkinsreporcart.git'
                echo 'Hello World'
            }
        }
           stage('build') {
            steps {
                echo 'Hello World'
                sh 'npm install'
                
            }
        }
           stage('deploy') {
            steps {
                echo 'Hello World'
                sh 'npm run build'
                
            }
        }
    }
}