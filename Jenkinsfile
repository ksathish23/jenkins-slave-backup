pipeline {
  agent any
  tools {
    maven 'Default'
  }
  stages {
    stage("Build") {
      steps {
        echo "hello building..."
      }
    }
    stage("Test") {
      steps {
        echo "testing..."
      }
    }
    stage("Package") {
      steps {
        echo "the packaging..."
      }
    }
  }
}
