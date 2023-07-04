@Library("library") _

pipeline {
    agent any
    
    stages {
        stage('cloning') {
            steps {
                script {
                    cloning("https://github.com/Rahul-Palande11/SRE-PATH.git", "main")
                }
            }
        }

        stage('build') {
            steps {
                script {
                    build()
                }
            }
        }
    }
}
