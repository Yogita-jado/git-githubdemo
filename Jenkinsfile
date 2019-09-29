pipeline{
    
    agent any
    stages{
        stage('compile stage')
        steps{
            withmaven(maven : 'maven-3'){
                sh 'mvn clean package'
            }
            
        }
        
    }
}
