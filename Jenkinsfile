
node {
    // uncomment these 2 lines and edit the name 'node-6.9.5' according to what you choose in configuration
    def nodeHome = tool name: 'node-6.9.5', type: 'jenkins.plugins.nodejs.tools.NodeJSInstallation'
    env.PATH = "${nodeHome}/bin:${env.PATH}"

    stage('check tools') {
        sh "node -v"
        sh "npm -v"
    }
}
