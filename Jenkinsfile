pipeline {
    agent any
    tools {
        jdk 'JDK11'
    }
    stages {
        stage('build') {
            steps {
                echo 'Hello world'
                sh 'mvn --version'
                echo 'Print version'
                sh 'mvn clean compile'
                echo 'Maven Clean Compile done'
            }
        }
    }
}