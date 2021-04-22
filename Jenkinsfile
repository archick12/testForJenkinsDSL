job("job-dsl-artifactory-freestyle-generic-example") {
    scm {
        git("https://github.com/archick12/testForJenkinsDSL.git", "master")
    }

    configure { node ->
        node / 'buildWrappers' << 'org.jfrog.hudson.generic.ArtifactoryGenericConfigurator' {
            stage('QA - Checkout') {
              checkout scm
            }

              stage('QA - Read JSON') {
              checkout scm
            }
        }
    }
}