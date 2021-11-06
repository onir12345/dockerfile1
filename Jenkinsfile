node {
    checkout scm

    docker.withRegistry('https://hub.docker.com/', 'om3237555') {

        def customImage = docker.build("shumail12345/pipe1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
