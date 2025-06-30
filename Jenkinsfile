pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage("Build operation"){
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
