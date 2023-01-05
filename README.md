# charts
Helm Charts for Solborn Projects

## Prerequisites
- Golang 1.19+
- Helm 3+

## Usage
- Add the solborn helm chart repository
```bash
helm repo add solborn https://solborn.github.io/charts

helm repo update
```

- Test Templates with:
```bash
cd \<project_dir>/\<chart_dir>
helm template . > /tmp/merged_template.yaml
```

- Update the Helm Chart Repo Index with:
```bash
# From project root directory
helm repo index . --url  https://solborn.github.io/charts
```
