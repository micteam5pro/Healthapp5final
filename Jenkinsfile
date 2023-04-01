pipeline{
    agent any 
    stages{
        stage('1-clone'){
            steps{
                sh 'whoami'
            }
        }
        stage('2-test'){
            steps{
                sh 'lscpu'
            }
        }
        stage('3-location'){
            steps{
                sh 'pwd'
            }
        }
        stage('4-list'){
            steps{
                sh 'ls'
            }
        }
        stage('5-logs'){
            steps{
                sh 'echo "healthapp" '
            }
        }
        stage('6-systemcheck'){
            steps{
                sh 'uptime'
            }
        }
        stage('7-indentifier'){
            steps{
                sh '#!/bin/bash'
            }
        }
        stage('8-systemcheck'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('9-network info'){
            steps{
                sh 'cat /etc/passwd'
            }
        }
        
    }
}