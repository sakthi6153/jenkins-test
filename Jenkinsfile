pipeline {
    agent any

    parameters {
        string(defaultValue: "TEST", description: 'What environment?', name: 'userFlag')
        // choices are newline separated
        choice(choices: 'CI-Parent1\nCI-Parent2', description: 'What AWS region?', name: 'releaseRepo')
    }

    stages {
        stage("Get Sources From SCM") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
        stage("Static Code Analysis") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
        stage("Unit Testing") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
    }
}
