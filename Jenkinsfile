pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   withGradle {
    sh './gradlew assemble'
    sh './gradlew test'
  }

}
