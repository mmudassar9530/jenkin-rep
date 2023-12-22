pipeline{
  agent any
  stages{
    stage('Git clone'){
      steps{
              git 'https://github.com/mmudassar9530/jenkin-rep.git'

      }
    }
    stage('Testing'){
      steps{
        sh '''python3 f1.py
python2 f2.py'''
      }
    }
    stage('Deploy'){
      steps{
        sh 'echo "Pipeline completed"'
      }
    }
  }
}
