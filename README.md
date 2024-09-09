# RapidMiner Helm Charts

## Adding this repository to your lise

```bash
helm repo add rapidminer-charts-github https://rapidminer.github.io/charts/
helm repo update
```

## Listing available versions

```bash
helm search repo rapidminer-charts-github -l
```

## Fetching a specific version of the chart

```bash
# Example for version 2024.1.0: helm fetch rapidminer-charts-github/rapidminer-aihub --version 2024.1.0
helm fetch rapidminer-charts-github/rapidminer-aihub --version [version]
```bash
```

