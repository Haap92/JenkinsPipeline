#!/usr/bin/env groovy
pipeline {
    agent any
    environment {
        TEST_PREFIX = "HelloWorld!!"
        UPDATE = "I have been Updated!"
    }
    stages {
        stage("Hello World!!") {
            steps {
                sh 'printenv TEST_PREFIX'
                sh 'printenv UPDATE'
                
            }
        }
    }
}