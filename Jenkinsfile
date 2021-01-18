pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-tutorial-test-3"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test-3/file1 ~/jenkins-tutorial-test-3/file2"
                }
            }
        }
}
