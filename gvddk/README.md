# Gvddk

Gvddk is a Golang wrapper to access the VMware Virtual Disk Development Kit API (VDDK), which is a SDK to help developers create applications that access storage on virtual machines. Gvddk provide two level apis to user:

* Low level api, which expose all VDDK apis directly in Golang.
* High level api, which provide some common used functionalities to user, such as IO read and write.

User can choose to either use main functionality via high level api, or use low level api to implement his own function combination.

# Documentation

See [GvddK Functional Specification](https://confluence.eng.vmware.com/display/~wxinyan/Gvddk+Functional+Specification)