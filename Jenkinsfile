node {
    stage('First') {
        def ubuntu = docker.image('ubuntu:latest')
        ubuntu.inside {
            sh 'touch index.html'
            sh 'ls -la > results.txt'
        }
    }
}
