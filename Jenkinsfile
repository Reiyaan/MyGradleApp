node {

    stage('Checkout') {
        git 'https://github.com/Reiyaan/MyGradleApp.git'
    }

    stage('Build') {
        sh 'gradle build'
    }

    stage('Test') {
        sh 'gradle test'
    }

}
