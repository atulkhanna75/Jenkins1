pipeline {
    agent any 
    tools {
        maven "Maven"
    
    }
    stages {
        stage('Compile ') { 
            steps {
                // Run Maven on a Unix agent.
                sh "javac Demo.java"
            }
        }
        stage('run') { 
            
            steps {
                sh "java Demo"
            }
        }
        }
}