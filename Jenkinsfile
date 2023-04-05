node {
    /* Requires the Docker Pipeline plugin to be installed */
    docker.image('maven:3.9.0-eclipse-temurin-11').inside('-v $HOME/.m2:/root/.m2') {
        stage('Build') {
            sh 'mvn clean install'
        }
    }
}