# app-helm-chart


![Version: 0.1.0-alpha1](https://img.shields.io/badge/Version-0.1.0--alpha1-informational?style=flat-square)

A Helm chart template for applications

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| PersistentVolumeClaim.annotations | string | `nil` |  |
| PersistentVolumeClaim.enabled | bool | `false` |  |
| PersistentVolumeClaim.labels | string | `nil` |  |
| PersistentVolumeClaim.mountPVC | bool | `false` |  |
| appEnv | string | `"dev"` |  |
| appName | string | `"example-app"` |  |
| appVersion | string | `"0.0.1"` |  |
| commonAnnotations | string | `nil` |  |
| commonLabels | string | `nil` |  |
| configMap.annotations | string | `nil` |  |
| configMap.configs | string | `nil` |  |
| configMap.enabled | bool | `false` |  |
| configMap.labels | string | `nil` |  |
| cronJob.enabled | bool | `false` |  |
| cronJob.jobs | string | `nil` |  |
| customResources | string | `nil` |  |
| deployment.affinity | object | `{}` |  |
| deployment.annotations | string | `nil` |  |
| deployment.containerPorts | string | `nil` |  |
| deployment.containerSecurityContext | string | `nil` |  |
| deployment.enabled | bool | `false` |  |
| deployment.envConfigMaps | string | `nil` |  |
| deployment.envMap | string | `nil` |  |
| deployment.envSecrets | string | `nil` |  |
| deployment.envVariables | string | `nil` |  |
| deployment.hostAliases | string | `nil` |  |
| deployment.initContainers | string | `nil` |  |
| deployment.labels | string | `nil` |  |
| deployment.lifecycle | string | `nil` |  |
| deployment.livenessProbe | string | `nil` |  |
| deployment.matchLabels | string | `nil` |  |
| deployment.nodeSelector | string | `nil` |  |
| deployment.readinessProbe | string | `nil` |  |
| deployment.replicas | int | `1` |  |
| deployment.resources | object | `{}` |  |
| deployment.securityContext | string | `nil` |  |
| deployment.serviceAccount.enabled | bool | `false` |  |
| deployment.sidecar | string | `nil` |  |
| deployment.startupProbe | object | `{}` |  |
| deployment.strategy | string | `"RollingUpdate"` |  |
| deployment.tolerations | string | `nil` |  |
| deployment.topologySpreadConstraints | string | `nil` |  |
| deployment.volumeMounts | string | `nil` |  |
| deployment.volumes | string | `nil` |  |
| externalSecret.enabled | bool | `false` |  |
| externalSecret.refreshInterval | string | `"2s"` |  |
| externalSecret.secretStore.name | string | `"vault-backend"` |  |
| externalSecret.secrets | string | `nil` |  |
| image.args | string | `nil` |  |
| image.command | string | `nil` |  |
| image.port | int | `8080` |  |
| image.registry | string | `"docker.io"` |  |
| image.repository | string | `"nginx"` |  |
| image.tag | string | `"1.0.0"` |  |
| ingress.annotations | string | `nil` |  |
| ingress.enabled | bool | `false` |  |
| ingress.entries | string | `nil` |  |
| job.enabled | bool | `false` |  |
| job.jobs | string | `nil` |  |
| keda.enabled | bool | `false` |  |
| keda.scaledObject.enabled | bool | `false` |  |
| keda.scaledObject.spec.triggers | list | `[]` |  |
| keda.scaledObject.spec.triggersMap | object | `{}` |  |
| keda.triggerAuthentication | string | `nil` |  |
| namespaceOverride | string | `nil` |  |
| podDisruptionBudget.enabled | bool | `false` |  |
| podDisruptionBudget.minAvailable | int | `1` |  |
| secret.annotations | string | `nil` |  |
| secret.enabled | bool | `false` |  |
| secret.lables | string | `nil` |  |
| secret.secrets | string | `nil` |  |
| service.annotations | string | `nil` |  |
| service.enabled | bool | `false` |  |
| service.labels | string | `nil` |  |
| service.ports | string | `nil` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.annotations | string | `nil` |  |
| serviceAccount.create | bool | `false` |  |
| serviceAccount.labels | string | `nil` |  |
| statefulSet.affinity | object | `{}` |  |
| statefulSet.annotations | string | `nil` |  |
| statefulSet.containerPorts | string | `nil` |  |
| statefulSet.containerSecurityContext | string | `nil` |  |
| statefulSet.enabled | bool | `false` |  |
| statefulSet.envConfigMaps | string | `nil` |  |
| statefulSet.envMap | string | `nil` |  |
| statefulSet.envSecrets | string | `nil` |  |
| statefulSet.envVariables | string | `nil` |  |
| statefulSet.hostAliases | string | `nil` |  |
| statefulSet.initContainers | string | `nil` |  |
| statefulSet.labels | string | `nil` |  |
| statefulSet.lifecycle | string | `nil` |  |
| statefulSet.livenessProbe | string | `nil` |  |
| statefulSet.matchLabels | string | `nil` |  |
| statefulSet.nodeSelector | string | `nil` |  |
| statefulSet.readinessProbe | string | `nil` |  |
| statefulSet.resources | object | `{}` |  |
| statefulSet.securityContext | string | `nil` |  |
| statefulSet.serviceAccount.enabled | bool | `false` |  |
| statefulSet.sidecar | string | `nil` |  |
| statefulSet.startupProbe | object | `{}` |  |
| statefulSet.tolerations | string | `nil` |  |
| statefulSet.topologySpreadConstraints | string | `nil` |  |
| statefulSet.updateStrategy | string | `"RollingUpdate"` |  |
| statefulSet.volumeClaimTemplates | string | `nil` |  |
| statefulSet.volumeMounts | string | `nil` |  |
| statefulSet.volumes | string | `nil` |  |
