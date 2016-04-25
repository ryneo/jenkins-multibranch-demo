stage 'Test'
node ('ubuntu') {
  sh 'echo Hello World!'
}

stage 'Two'
node ('jenkins-master') {
  sh 'echo Run stage two'
}
