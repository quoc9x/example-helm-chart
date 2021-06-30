# Helm Charts from quocnvc
Hi, I'm a DevOps engineer.

But you're free to use and contribute all Helm charts here. 

## Usage

Some common Helm commands for you

```
# Add repo before using
$ helm repo add qwrite https://raw.githubusercontent.com/qwrite/master/
"qwrite" has been added to your repositories

# Search for charts, or list all the charts by repo's name
$ helm search repo qwrite
NAME                	CHART VERSION	APP VERSION	DESCRIPTION
cuongquoc_vn/ambassador-ssl	0.1.0        	1.0.0      	A Helm chart for Kubernetes

# Get configurations (values file)
$ helm show values cuongquoc_vn/ambassador-ssl > myvalues.yaml

# Install chart with your configurations
$ helm install mywebsite-ssl cuongquoc_vn/ambassador-ssl
```

## List of charts

- Ambassador-SSL : install Let's Encrypt certificate for your Ambassador API Gateway (Ambassaador Edge Stack)
- _(updating new chart here...)_

