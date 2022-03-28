Welcome to the AlphaBravo Helm chart repository.

Below is a list of Helm charts and how to use them.

## ABScan

Add the repository.

```bash
helm repo add ablabs https://helm.ablabs.io/abscan
```

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

Update the ABScan repository:

```bash
helm repo update
```