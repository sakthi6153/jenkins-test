pipeline {
    agent any

    parameters {
        string(defaultValue: "TEST", description: 'Enter the Enviroment Name to deploy', name: 'userFlag')
        string(defaultValue: "TEST", description: 'Enter the service Repository Name', name: 'releaseRepository')
        // choices are newline separated
        choice(choices: 'CI-Parent1\nCI-Parent2', description: 'Select Respository Name from below?', name: 'releaseRepo')
    }

    stages {
        stage("Get Sources From SCM") {
            steps {
                currentBuild.name = "flag: ${params.userFlag}---flag: ${params.releaseRepo}"
                currentBuild.description = "flag: ${params.userFlag}---flag: ${params.releaseRepo}"
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
