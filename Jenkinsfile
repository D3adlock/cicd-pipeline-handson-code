node('devenv') {
    stage('build') {
        steps {
            sh 'echo "this is a build command place holder"'
        }
    }
    stage('deploy') {
        steps {
            sh 'rm /usr/share/nginx/html/index.html'
            sh 'cp index.html /usr/share/nginx/html/'
        }
    }
}
