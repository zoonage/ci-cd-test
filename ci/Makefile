set:
	fly -t platform set-pipeline -c main.yaml -p aaron-ci-cd-demo-simple

login:
	fly login -t platform -c https://localhost:8443 -k -n platform

port-forward:
	kubectl port-forward service/concourse-proxy 8443:8443 -n shared-services

