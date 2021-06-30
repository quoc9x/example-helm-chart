# Helm Charts from quocnvc
Hi, I'm a DevOps engineer.

But you're free to use and contribute all Helm charts here. 

## Usage

Some common Helm commands for you

```
# Add repo before using
$ helm repo add qwrite https://raw.githubusercontent.com/qwrite/example-helm-chart/master/
"qwrite" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo qwrite
NAME                	CHART VERSION	APP VERSION	DESCRIPTION
qwrite/mynginx	0.1.0        	latest      	A Helm chart for Kubernetes

# Get configurations (values file)
$ helm show values qwrite/mynginx > values.yaml

# Install chart with your configurations
$ helm install myangularapp qwrite/mynginx
```
