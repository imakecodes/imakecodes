pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        sh '''#!/bin/bash
flake8'''
      }
    }

  }
}