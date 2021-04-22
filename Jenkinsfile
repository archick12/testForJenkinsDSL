pipelineJob('job-dsl-plugin') {
  definition {
    cpsScm {
      scm {
        git {
          remote {
            url('https://github.com/archick12/testForJenkinsDSL.git')
          }
          branch('*/master')
        }
      }
      echo "test"
    }
  }
}