node {
    // Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
            echo "clone Success"
        }
        stage ('Build') {
            echo "Build Success"
        }
       
        stage ('Deploy') {
            echo "Deploy Success"
        }
    } catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
