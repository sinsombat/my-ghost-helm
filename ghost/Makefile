ns=$*

install.%:
	helm install --name my-ghost --namespace dev . -f values/values-${ns}.yaml

diff.%:
	helm diff upgrade my-ghost . -f values/values-${ns}.yaml

upgrade.%:
	helm upgrade my-ghost . -f values/values-${ns}.yaml