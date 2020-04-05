# Helm Charts Repository

To add charts and update `index.yaml`:
1. `git clone git@github.com:mkorejo/helm_charts.git && cd helm_charts`
1. Make changes to Helm charts in `src`
1. `helm package src/<chart_dir> -d ./releases`
1. `helm repo index . --url https://mkorejo.github.io/helm_charts/`
1. Push up the chart package(s) and `index.yaml`