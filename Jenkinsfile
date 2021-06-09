pipeline {
    agent any
    tools {
        jdk 'JDK11'
    }
    stages {
        stage('build') {
            steps {
                echo 'Hello world'
                bat 'mvn --version'
                echo 'Print version'
                bat 'mvn clean compile'
                echo 'Maven Clean Compile done'
            }
        }
    }
}