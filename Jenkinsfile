pipeline {
    agent any
    
    stages 
    {
        stage('Build') 
        {
            steps 
            
            {
                echo 'Build App'
            }
        }
        
        stage('Test') 
        {
            steps 
            
            {
                echo 'Testing App'
            }
        }
        
        stage('Deploy') 
        {
            steps 
            
            {
                echo 'Deploying App'
            }
        }
            
            
        }
        
        post
        {
            always 
            {
                emailext body: 'Summary of the Pipeline', subject: 'Pipeline Status', to: 'shubham.gupta1708@gmail.com'
            }
        }
    }
