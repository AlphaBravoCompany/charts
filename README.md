# AlphaBravo Helm Charts

Welcome to the AlphaBravo Helm chart repository.

Below is a list of Helm charts and how to use them.

## ABScan

Add the repository.

```bash
helm repo add abscan https://helm.ablabs.io/abscan
```

Install ABScan.

```bash
helm install --namespace abscan --create-namespace abscan abscan/abscan
```

Get Chart and Application version information.

```bash
helm search repo abscan
```

Update the ABScan repository:

```bash
helm repo upgrade
```