pipeline{
  agent any
  stages{
    stage('Git clone'){
      steps{
              git 'https://github.com/mmudassar9530/jenkin-rep.git'

      }
    }
    stage('Code Testing'){
      steps{
      sh  '''python3 f1.py
        python3 f2.py'''
      }
    }
    stage('deploy'){
    steps{
      sh 'echo "Pipeline completed."'
    }
  }
}
}
