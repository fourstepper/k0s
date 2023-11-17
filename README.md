# k0s

A git repository containing definitions of my running clusters.

## Bootstrap steps

Generate config for a new cluster:

```bash
k0sctl init > newcluster.yaml
```

Apply and generate kubeconfig:

```bash
k0sctl apply --config newcluster.yaml --kubeconfig-out ~/.kube/new-cluster-config
```
