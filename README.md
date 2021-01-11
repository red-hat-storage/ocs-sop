# ocs-sop
Standard Operating Procedure Documents for OpenShift Container Storage

## Assumptions
The final configuration details for OCS on OSD are TBD. These SoPs are written with the assumptions listed below.

### Setup
  * Deployed on AWS and follows all OSD guidelines where possible.
  * Dynamic provisioning, not local.
  * Storage capacity is expanded by scaling out. (i.e. adding nodes)
  * Rook-Ceph toolbox is deployed.

### Policy
  * You have permission to proceed with the SoP instructions.
  * You do not have permission to delete any customer data in order to free space. Expansion is the only option.

### Other
  * Customer notifications and communication is outside the scope of these documents.

