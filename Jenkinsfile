@Library("library") _

pipeline {
    agent any

    stages {
        stage('cloning') {
            steps {
                git branch: "main", url: "https://github.com/Rahul-Palande11/SRE-PATH.git"
            }
        }

        stage('build') {
            steps {
                
                call()
            }
        }
    }
}
