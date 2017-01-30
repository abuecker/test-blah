#!/bin/env groovy

stage('build') {
  docker.image('node:6.9').inside {
    println 'Build something cool'
    checkout_scm
    sh 'ls -al'
  }
}
