# github-label-manager

To sync and manage the labels I use

## Inspiration

The [Label Sync](https://github.com/marketplace/actions/label-sync) Github Action by @EndBug

Label Exporter - https://github.com/marketplace/actions/export-label-config

---

name: Sync labels
on:
workflow_dispatch:

jobs:
labels: null
runs-on: ubuntu-latest
steps: - uses: EndBug/label-sync@v2
with: null
config-file: .github/labels.yml
source-repo: owner/repo
request-token: ${{ secrets.YOUR_OWN_SECRET }}
delete-other-labels: false
dry-run: true
token: ${{ secrets.GITHUB_TOKEN }}
