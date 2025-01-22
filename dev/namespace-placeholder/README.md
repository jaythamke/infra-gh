# Namespace-placeholder

It is a namespace manifest with name 'foo' with empty labels and annotations
and is useful to create namespace resources on infra cluster.
As K8s Kustomization cannot create a namespace resource therefore it is required,
additionally K8s Kustomization then overrides the name, labels, annotations etc.
