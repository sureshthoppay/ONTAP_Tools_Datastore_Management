# ONTAP Tools Datastore Management
Sample Ansible Playbook utilizing ONTAP Tools for VMware vSphere to manage the Datastore.

NetApp ONTAP Tools for VMware vSphere provides an unified appliance which include Virtual Storage Console (VSC), VASA Provider and Storage Replication Adapter (SRA) for NetApp ONTAP.
ONTAP Tools registers with VMware vCenter as a plug-in and allows to provision traditional datastores (VMFS and NFS) as well as vVol datastores for supported SAN and NAS protocols.

This ONTAP Tools sample role uses ONTAP Tools RESTful API to automate provisioning of following VMware Datastores.

* VMFS with iSCSI
* NFS (FlexVol as well as FlexGroup)
* vVol with iSCSI (Single FlexVol as well as Multiple FlexVols)
* vVol with NFS (Single FlexVol as well as Multiple FlexVols)


