pipeline {
    agent any

    stages {
        stage("Checkout code"){
            // checkout the repository
            steps {
                git branch: 'main', url: 'https://github.com/mihaildimiev/JenkinsSeleniumIdeDemoRepo_1_8'
            }
        }
    }
}