node {
    stage('First') {
        echo 'Hello World'
        env.WORKSPACE = pwd()
        echo "${env.WORKSPACE}"
        def ubuntu = docker.image('ubuntu:latest')
        ubuntu.inside {
            echo 'Inside docker'
        }
    }
}
