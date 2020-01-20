node('devenv') {
    stage('build') {
        checkout scm: scm
    }
    stage('build') {
        sh 'echo "this is a build command place holder"'
    }
    stage('deploy') {
        sh 'rm /usr/share/nginx/html/index.html'
        sh 'cp index.html /usr/share/nginx/html/'
    }
}
