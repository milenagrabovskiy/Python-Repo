pipeline {
    agent any

    stages {

        stage("set env") {
            steps {
                echo "create and activate venv"
                echo "set environment variables and secrets"
            }
        }

        stage("build") {
            steps {
                echo "install dependencies from requirements.txt"
                echo "build docker container"
            }
        }

        stage("tests smoke fe") {
            steps {
                echo "running fe smoke test 1"
                echo "running fe smoke test 2"
            }
        }

        stage("tests regression fe") {
            steps {
                echo "running fe regression test 1"
                echo "running fe regression test 2"
            }
        }

        stage("tests smoke be") {
            steps {
                echo "running be smoke test 1"
                echo "running be smoke test 2"
            }
        }

        stage("tests regression be") {
            steps {
                echo "running be regression test 1"
                echo "running be regression test 2"
            }
