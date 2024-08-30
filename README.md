# WireGuard Easy

> NOTE: This chart is forked from hansehe's one ([Artifact HUB](https://artifacthub.io/packages/search?repo=wg-easy), [GitHub](https://github.com/hansehe/wg-easy-helm))
> Use `https://raw.githubusercontent.com/haeramkeem/wg-easy-helm/main/helm/charts` for repo URL to use forked one

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/wg-easy)](https://artifacthub.io/packages/search?repo=wg-easy)

The WireGuard Easy deploys a vpn solution, check out:
- https://github.com/wg-easy/wg-easy

## Run With Docker
```bash
docker-compose -f docker-compose.yml up
```

Access WireGuard Easy at: 
- http://localhost:8282/
- Password (see docker-compose.yml) => password

## Use Helm Repo
```bash
helm repo add wg-easy https://raw.githubusercontent.com/hansehe/wg-easy-helm/master/helm/charts
helm repo update
```
```bash
helm install wg-easy wg-easy/wg-easy
```

