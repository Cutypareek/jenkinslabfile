pipeline {
    agent any
    stages{
    stage ('sample1'){
        steps{
        echo 'Building...'
        bat 'python practice.py'
            }
    }
    stage ('sample2'){
        steps{
        echo 'Using maven'
        }
    }
}
}
