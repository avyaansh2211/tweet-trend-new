pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/avyaansh2211/tweet-trend-new.git'
            }
        }
    }
}
