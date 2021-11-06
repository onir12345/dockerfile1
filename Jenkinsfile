node {
    checkout scm

    docker.withRegistry('https://hub.docker.com', 'shumail12345') {

        def customImage = docker.build("shumail12345/pipe1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
