ns=$*

install.%:
	helm install --name mariadb --namespace dev . -f values/values-${ns}.yaml

diff.%:
	helm diff upgrade mariadb . -f values/values-${ns}.yaml

upgrade.%:
	helm upgrade mariadb . -f values/values-${ns}.yaml