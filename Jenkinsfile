node {
	def app
	stage('Deploy image') {
		sh "gofabric8 deploy -y"
		sh "gofabric8 secrets -y"
		sh "kubectl get pods"
	}
}
