# JMeter Helm Charts

[Helm](https://helm.sh) repo for different charts related to JMeter which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add liukunup https://liukunup.github.io/helm-charts
helm repo update
```

### Helm Charts

* [JMeter](https://liukunup.github.io/helm-charts/)

  ```bash
  helm install my-release liukunup/jmeter
  ```
  
  ```bash
  helm delete my-release
  ```