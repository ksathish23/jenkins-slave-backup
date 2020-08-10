pipeline {
  agent any
  tools {
    gradle 'Default'
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
        echo "packaging..."
      }
    }
  }
}
