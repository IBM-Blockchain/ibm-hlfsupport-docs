# yaml-files 

This branch contains `yaml` files required for deploying IBM Support for the Hyperledger Fabric offering.

### SCC for OCP
By default, `allowPrivilegedContainer` and `allowPrivilegeEscalation` will be set to `false`. See `operator/ocp/scc/ibm-hlfsupport-scc.yaml`.

For HSM-enabled deployments and deployments using v1.4 dind peers, an alternative SCC, where `allowPrivilegedContainer` and `allowPrivilegeEscalation` are set to `true` will be required. See `operator/ocp/scc/ibm-hlfsupport-scc-privileged.yaml`.