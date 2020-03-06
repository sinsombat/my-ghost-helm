ns=$*

install.%:
	helm install --name mysql --namespace dev . -f values/values-${ns}.yaml

diff.%:
	helm diff upgrade mysql . -f values/values-${ns}.yaml

upgrade.%:
	helm upgrade mysql . -f values/values-${ns}.yaml