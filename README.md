# Helm charts
This is a small repository with some charts, mostly with the templates for new projects.

### How to add a new chart

* Upload the source into `/sources` folder
* Check and Lint the chart `helm lint <chart>`
* Rebuild the repo index `helm repo index --url https://corvax.github.io/helm-charts/ .`

### How to use the repo

* Add repo in your helm client `helm repo add my-charts https://corvax.github.io/helm-charts/`
