# Gateway MASTER downloads

Windows MSI installers and automatic update manifests for Gateway MASTER.

- [Download the latest installer](https://github.com/metodivancic/gateway-master-releases/releases/latest/download/GatewayMASTER.msi)
- [Latest version manifest](https://github.com/metodivancic/gateway-master-releases/releases/latest/download/latest.json)
- [Release history](https://github.com/metodivancic/gateway-master-releases/releases)

In Gateway Updater, set the GitHub update URL to:

```text
https://github.com/metodivancic/gateway-master-releases/releases/latest/download/latest.json
```

Each stable release contains `GatewayMASTER.msi` and `latest.json`. The manifest identifies the application version, the version-specific MSI download, and its SHA-256 checksum.

Existing customer database TXT files are supplied separately and are not replaced by updates. The installer includes the application-managed `Gatewaydataclass.txt` file.

Application source code and customer configuration files are not hosted in this repository.
