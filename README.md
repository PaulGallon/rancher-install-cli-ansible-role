# ansible-rancher-tools

Ansible role to install Rancher CLI and Rancher Compose.

Role Variables
--------------

The following variables are available. Their default values are shown here.

```
rancher_cli_install: true
rancher_cli_download_url: https://github.com/rancher/cli/releases/download/v0.6.7/rancher-linux-amd64-v0.6.7.tar.gz
rancher_compose_install: true
rancher_compose_download_url: https://github.com/rancher/rancher-compose/releases/download/v0.12.5/rancher-compose-linux-amd64-v0.12.5.tar.gz
rancher_access_key: 'YOUR_ACCESS_KEY'
rancher_secret_key: 'YOUR_SECRET_KEY'
rancher_url: 'https://rancher/v2-beta/schemas'
rancher_environment: '1a5'
```
License
-------

Apache License 2
