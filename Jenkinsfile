pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo '$GIT_BRANCH'
            }
        } 
        stage('HelloPowerShell') {
            steps 
            {
                powershell 'Write-Output "Counting from 1 to 9 (in seconds):"'
            }
        }}}
