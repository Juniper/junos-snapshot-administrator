junos-snapshot-administrator
============================
Junos Snapshot Administrator enables you to capture and audit runtime
environment snapshots of your networked devices running the Junos operating
system (Junos OS). You can capture and validate the operational status of a
device and review operational changes to a device. You create configuration
files that define the scope of snapshots and customize the evaluation criteria
for the snapshot data.

Junos Snapshot Administrator can perform the following functions on either a
single device or list of devices running Junos OS:

* Take a snapshot of the runtime environment on a device.
* Compare two snapshots.
* Audit a device's runtime environment against pre-defined criteria.

For example, prior to a software or hardware upgrade on a device, you can take a
pre-install and post-install snapshot of the device and then compare the two
snapshots. You can then review the operational changes on the device and
validate these changes from a list of expected changes.

# Recommended Junos Release
Junos Snapshot Administrator can be used with any device running Junos OS.
We recommend using Junos OS Release 9.6 or later release. 
For more information about Junos OS releases, refer to the Juniper Networks 
technical documentation site at 
https://www.juniper.net/techpubs/en_US/release-independent/junos/information-products/pathway-pages/junos/product/index.html .

JSNAPy
------
If you are new user and planning to use Junos Snapshot Administrator, Prefer
using [JSNAPy](https://github.com/Juniper/jsnapy)

Contributions
-------------
Interested in sharing criteria that you have written with the community? Add it to the contrib directory. 

Please contact jnpr-community-netdev@juniper.net for any queries.
