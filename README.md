# GitOps for Robotic Edge

## Quick Start

NOTE: you may have to run commands below multiple times to allow time for
certain resources to become available.

Install operators in OpenShift

```sh
oc apply -k components/operators
```

Install components for the demo

```sh
oc apply -k components/demo
```
