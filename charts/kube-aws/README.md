# kube-aws

![Version: 1.15.0](https://img.shields.io/badge/Version-1.15.0-informational?style=flat-square) ![AppVersion: 1.13.8](https://img.shields.io/badge/AppVersion-1.13.8-informational?style=flat-square)

A Helm chart to install litmus aws chaos experiments

**Homepage:** <https://litmuschaos.io>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| jasstkn | jasssstkn@yahoo.com |  |
| ksatchit | karthik@chaosnative.com |  |
| uditgaurav | udit@chaosnative.com |  |

## Source Code

* <https://github.com/litmuschaos/litmus>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| customLabels | object | `{}` | Additional labels |
| experiments.disabled | list | `[]` |  |
| fullnameOverride | string | `"kube-aws"` |  |
| image.litmusGO.pullPolicy | string | `"Always"` |  |
| image.litmusGO.repository | string | `"litmuschaos/go-runner"` |  |
| image.litmusGO.tag | string | `"1.13.8"` |  |
| nameOverride | string | `"kube-aws"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)