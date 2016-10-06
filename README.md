# Stack4things
Stack4Things is a framework for Cloud-based management of IoT resources integrated with OpenStack. Stack4Things involves two main components: the IoTronic service and the Lightning-rod probe. IoTronic is the Cloud-side service that allows users to manage IoT resources. Lightning-rod is the IoT device-side probe that acts as the IoTronic counterpart connecting the device to the Cloud. 

We currently have two versions of Stack4Things. 

The first version of Stack4Things is the standalone one. It implements all the features that have been currently designed. Both components are implemented in Node.js. Stack4things is its standalone version is only partially integrated with OpenStack (it can use the Neutron service as a back-end for networking management). This version has been implemented mainly for research reasons. A draft of a Web dashboard is also available for the standalone version. 

The second version of Stack4Things is the OpenStack-based one. In this case, the IoTronic service is implemented in the form of an OpenStack service in Python. The Lightning-rod probe is still implemented in Node.js. This version only implements basic functionalities but it is hosted on the StackForge, the OpenStack continuous integration system. 

The two version will eventually converge. 

You can find the repositories for the standalone version of Stack4Things here:

[s4t-iotronic-standalone](https://github.com/MDSLab/s4t-iotronic-standalone)

[s4t-lightning-rod](https://github.com/MDSLab/s4t-lightning-rod)

[s4t-iotronic-webinterface] (https://github.com/MDSLab/s4t-iotronic-webinterface)

while the repositories for the OpenStack-based version of Stack4Things can be found here:

[iotronic](https://github.com/MDSLab/iotronic)

[iotronic-lightning-rod](https://github.com/MDSLab/iotronic-lightning-rod)

[python-iotronicclient](https://github.com/MDSLab/python-iotronicclient)
