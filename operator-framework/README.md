- An `Operator` represents human operational knowledge in software, to reliably manage an application.
- An Operator is an application-specific controller that extends the Kubernetes API to create, configure, and manage instances of complex stateful application on
behalf of a kubernetes user. It builds upon the basic kubernetes resource controller concepts but includes domain or application-specific knowledge to automate common
tasks.

There are mainly three things:

1. Resource --> Pod, ConfigMap, Route
2. Controller --> ReplicaSet, DaemonSet, Deployments
3. Knowledge

- Route is also known as `Ingress`.
- Operators take advantage of `Custom Resource Definitions (CRDs)`. CRDs allows us to extend the Kubernetes API.

- `oc` is the client for OpenShift.
- A custom resource needs a controller to act upon its presence.
