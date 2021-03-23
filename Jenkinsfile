node('devenv') {
    stage('checkout') {
        checkout scm: scm
    }
    stage('build') {
        sh 'this is failed build'
    }
    stage('deploy') {
        sh 'rm /usr/share/nginx/html/index.html'
        sh 'cp index.html /usr/share/nginx/html/'
    }
}
