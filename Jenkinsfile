#!/usr/bin/env groovy
pipeline {
    agent any
    environment {
        TEST_PREFIX = "HelloWorld!!"
    }
    stages {
        stage("Hello World!!") {
            steps {
                sh 'printenv TEST_PREFIX'
                sh './JenkinsPipeline/scripts/update.sh'
            }
        }
    }
}