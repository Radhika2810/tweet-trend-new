pipeline {
    agent {
        node {
            label 'maven'
        }
    } 

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Radhika2810/tweet-trend-new.git'
            }
        }
    }
}
