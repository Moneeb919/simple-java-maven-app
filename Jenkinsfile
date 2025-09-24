pipeline {
    agent any
    tools{
        maven 'Default'
    }
    stages {
        stage('Build') { 
            steps {
                bat 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
