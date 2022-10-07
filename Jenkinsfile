pipeline{
    agent any
    stages{
        stage('Git Clone'){
            steps{
                git branch: 'main', url: 'https://github.com/mvivek0210/Samplefirstproject.git'
            }
        }
        
        stage('Testing'){
            steps{
                echo "Testing over"
            }
        }
        
         stage('Build'){
            steps{
                echo "Build over"
            }
        }
    }
}
