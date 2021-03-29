# ocs-sop
Standard Operating Procedure Documents for OpenShift Container Storage

## Assumptions
The final configuration details for OCS on OSD are TBD. These SoPs are written with the assumptions listed below.

### Setup
  * Deployed on AWS and follows all OSD guidelines where possible
  * Intermnal mode
  * Dynamic provisioning
  * Storage capacity is expanded by scaling the present machinese.
  * The workerocs machineset is deployed
  * Rook-Ceph toolbox is deployed
  * Data encryption is not enabled 

### Policy
  * You have permission to proceed with the SoP instructions.
  * You do not have permission to delete any customer data in order to free space. Expansion is the only option.

### Other
  * Customer notifications and communication is outside the scope of these documents.

### Build Notes
https://gitlab.com/antora/antora-asciidoctor-extensions/-/tree/master/tabs-block used for tabs. Requires merging styles.css, copying behvaior.js to ui/js. 
