none:

helm-template:
	helm template vms vm/victoria-metrics-single -f values.yaml -n victoria --debug --dry-run | yq . > manifest.yaml
