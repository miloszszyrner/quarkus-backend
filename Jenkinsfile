pipeline {
    agent any 
    tools {
        maven 'maven-3.9.7'
    }
    stages {
        stage('Build') { 
            steps {
               sh 'mvn -B -DskipTests clean package' 
            }
        }
        stage('Test') { 
            steps {
                sh 'echo Test'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo Deploy'
            }
        }
    }
}
