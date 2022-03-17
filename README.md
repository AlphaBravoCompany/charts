Welcome to the AlphaBravo Helm chart repository.

Below is a list of Helm charts and how to use them.

## ABScan

Add the repository.

```bash
helm repo add abscan https://helm.ablabs.io/abscan
```

Generate a values.yaml file.

```bash
helm show values abscan > my_values.yaml
```

Install ABScan.

```bash
helm install -f my_values.yaml --namespace abscan --create-namespace abscan abscan/abscan
```

Get Chart and Application version information.

```bash
helm search repo abscan
```

Update the ABScan repository:

```bash
helm repo upgrade
```