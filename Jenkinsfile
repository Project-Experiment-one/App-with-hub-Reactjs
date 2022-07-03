#!groovy

node () {
    stage('Dev') {
        echo 'This is the Job1 inside the dev environment in the first place'
        functionInstall('Dev')
    }
    stage('Test') {
        echo 'This is the Job2 inside the Test environment in the second place'
        functionInstall('Test')
    }
    stage('QA') {   
        echo 'This is the Job3 inside the QA environment in the third place'
        functionInstall('QA')
    }
    stage('XAT') {
        ehco 'This is the Job4 inside the XAT environment in  the fourth place'
        functionInstall('XAT')
    }
    stage('Prod') {
        echo 'This is the Job5 inside the Prod environment in the fifth place'
        functionInstall('Prod')
    }
}
def functionInstall(env) {
    echo "This is the function call in the jenkinsfile in "+env
}
