pipeline {
    agent any
    tools{
        mavan 'Default'
    }
    stages {
        stage('Build') { 
            steps {
                bat 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
