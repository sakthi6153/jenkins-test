pipeline {
    agent any

    parameters {
        string(defaultValue: "TEST", description: 'What environment?', name: 'userFlag')
        string(defaultValue: "TEST", description: 'What environment?', name: 'userFlag')
        // choices are newline separated
        choice(choices: 'CI-Parent1\nCI-Parent2', description: 'Which Repository?', name: 'releaseRepo')
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
        stage("Build Package") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
         stage("Containarizing Artifacts") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
         stage("Push Artifacts to Nexus") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
         stage("Deploy to Kubernetes") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
         stage("Contract Testing") {
            steps {
                echo "flag: ${params.userFlag}"
                echo "flag: ${params.releaseRepo}"
            }
        }
    }
}
