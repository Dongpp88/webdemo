node {
    checkout scm

    def customImage = docker.build("webdemo")

    customImage.inside {
        sh 'make test'
    }
}
