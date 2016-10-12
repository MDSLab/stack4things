# Stack4things

##Overview

Stack4Things is an Internet of Things framework developed by the Mobile and Distributed Systems Lab (MDSLab) at the University of Messina, Italy. Stack4Things is an open source project that helps you in managing IoT device fleets without caring about their physical location, their network configuration, their underlying technology. It is a Cloud-oriented horizontal solution (integrated with OpenStack) providing IoT object virtualization, customization, and orchestration. Stack4Things provides you with an out-of-the-box experience on several of the most popular embedded and mobile systems.

You can find more information on the official Web site: [http://stack4things.unime.it](http://stack4things.unime.it). 

Stack4Things involves two main components: the IoTronic service and the Lightning-rod probe. IoTronic is the Cloud-side service that allows users to manage IoT resources. Lightning-rod is the IoT device-side probe that acts as the IoTronic counterpart connecting the device to the Cloud. 

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

##Get started with Stack4Things

Coming soon!

##Scientific References

Scientific papers describing the work on Stack4Things by the University of Messina can be found [here](http://mdslab.unime.it/biblio).

In particular, you can find details about Stack4Things in the following papers:

G. Merlino, D. Bruneo, S. Distefano, F. Longo, A. Puliafito - Stack4Things: integrating IoT with OpenStack in a Smart City context. Sensors and Smart Cities, Smart Computing Workshops (SMARTCOMP Workshops), 2014 International Conference on, pp. 21,28, 5-5 Nov. 2014.

G. Merlino,  D. Bruneo,  S. Distefano,  F. Longo,  A. Puliafito, and A. Al-Anbuky - A Smart City Lighting Case Study on an OpenStack-Powered Infrastructure, Sensors 2015, 15(7), pp. 16314-16335.

G. Merlino, D. Bruneo, F. Longo, S. Distefano, A. Puliafito - Cloud-based network virtualization: An IoT use case (2015) Lecture Notes of the Institute for Computer Sciences, Social-Informatics and Telecommunications Engineering, LNICST, 155, pp. 199-210. 

F. Longo, D. Bruneo, S. Distefano, G. Merlino, A. Puliafito - Stack4Things: An OpenStack-Based Framework for IoT (2015) Proceedings - 2015 International Conference on Future Internet of Things and Cloud, FiCloud 2015 and 2015 International Conference on Open and Big Data, OBD 2015, art. no. 7300819, pp. 204-211.

G. Merlino, D. Bruneo, S. Distefano, F. Longo, A. Puliafito - Enabling mechanisms for Cloud-based network virtualization in IoT (2015) IEEE World Forum on Internet of Things, WF-IoT 2015 - Proceedings, art. no. 7389064, pp. 268-273.

F. Longo, D. Bruneo, S. Distefano, G. Merlino, A. Puliafito - Stack4Things: a sensing-and-actuation-as-a-service framework for IoT and cloud integration (2016) Annales des Telecommunications/Annals of Telecommunications, pp. 1-18.
