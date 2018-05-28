pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
    }

    stages {
        stage("Get Sources From SCM") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
        stage("Static Code Analysis") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
        stage("Unit Testing") {
            steps {
                echo "flag: ${params.userFlag}"
            }
        }
    }
}
