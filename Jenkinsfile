pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('stage1') {
      agent {
        node {
          label 'clean'
        }

      }
      steps {
        sh '''#!/bin/bash


make clean
'''
      }
    }
  }
}