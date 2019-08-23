node {
    checkout scm

    docker.withRegistry('https://hub.docker.com', 'Docker_Hub') {

        def customImage = docker.build("alkasamant/alkasamant1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
