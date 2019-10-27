# Contoso Cluster Config

This is an example repository.

- [namespaces](./namespaces): creates three namespaces for the cluster: `itops`, `appteam-frauddetection`, and `appteam-refrigcontrol`, these namespaces are managed by the IT cluster operator
- [cluster-apps](./cluster-apps): contains applications deployed by an IT cluster operator, e.g. common monitoring or logging agent
- [appteam-registerdetection](./appteam-frauddetection): contains a ConfigMap produced by IT cluster operator to communicate some configuration to an application team
