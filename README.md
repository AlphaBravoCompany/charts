Welcome to the AlphaBravo Helm chart repository.

Below is a list of Helm charts and how to use them.

## Add the Repository to Helm
Add the repository.

```bash
helm repo add ablabs https://helm.ablabs.io/charts
```

## Update the Repository
Update the ABLabs repository:

```bash
helm repo update
```

## Install ABScan
Generate a values.yaml file.

```bash
helm show values ablabs/abscan > my_values.yaml
```

Install ABScan.

```bash
helm install -f my_values.yaml --namespace abscan --create-namespace abscan ablabs/abscan
```

Get Chart and Application version information.

```bash
helm search repo abscan
```

## Install CVE-Search Database Updater
Generate a values.yaml file.

```bash
helm show values ablabs/cve-search > my_values.yaml
```

Install CVE-Search.

```bash
helm install -f my_values.yaml --namespace abscan --create-namespace abscan ablabs/cve-search
```

Get Chart and Application version information.

```bash
helm search repo cve-search
```
