



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# oVirt APIs






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### KS oVirt Boot WinPE Recreate Virtual Machine


### oVirt Recreate Virtual Machine





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| oVirt: Bios Type | Text | `ovirtbiostype` | Valid Values are (they must be in all capitals):<br>1. CLUSTER_DEFAULT - Use the cluster-wide default.<br>2. I440FX_SEA_BIOS - i440fx chipset with SeaBIOS.<br>3. Q35_OVMF - q35 chipset with OVMF (UEFI) BIOS.<br>4. Q35_SEA_BIOS - q35 chipset with SeaBIOS.<br>5. Q35_SECURE_BOOT- q35 chipset with OVMF (UEFI) BIOS with SecureBoot enabled.<br><br>https://ovirt.github.io/ovirt-engine-api-model/4.5/#types/bios_type |
| oVirt: Cluster Name | Text | `ovirtclustername` |  |
| oVirt: CPU Count | Text | `ovirtcpucount` |  |
| oVirt: Disk Interface | Text | `ovirtdiskinterface` | SATA or IDE required for Windows<br>VIRTIO_SCSI for windows after driver install<br>VIRTIO for Linux |
| oVirt: Disk Storage Name | Text | `ovirtdiskstoragename` |  |
| oVirt: Engine API User | Basic Credential | `ovirtengineapiuser` |  |
| oVirt: Engine Server | Basic Node | `ovirtengineserver` |  |
| oVirt: Memory Size | Text | `ovirtmemorysize` |  |
| oVirt: Network Name | Text | `ovirtnetworkname` |  |
| oVirt: NIC Interface | Text | `ovirtnicinterface` | E1000 for Windows<br>VIRTIO for Linux |
| oVirt: TimeZone | Text | `ovirttimezone` |  |
| Kickstart Worker Linux Node | Linux/Unix Node | `kickstartworkerlinuxnode` | Linux refers to both Linux and MacOS |
| Kickstarted Node | Basic Node | `kickstartednode` |  |
| kickstartWorkerBuildLinuxUser | Linux/Unix Credential | `kickstartworkerbuildlinuxuser` |  |
| KS: Attune Base Dir | Text | `ksattunebasedir` |  |
| oVirt: Datacenter Name | Text | `ovirtdatacentername` |  |
| oVirt: VM Comment | Text | `ovirtvmcomment` | Input to the comment text field in the vm struct https://ovirt.github.io/ovirt-engine-api-model/4.5/#types/vm. |
| oVirt: VM Description | Text | `ovirtvmdescription` | Input to the description text field in the vm struct https://ovirt.github.io/ovirt-engine-api-model/4.5/#types/vm. |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
