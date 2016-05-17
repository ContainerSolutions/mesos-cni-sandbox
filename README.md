# mesos-cni-sandbox

# Background

This is a sandbox repository to experiment with the CNI support in Mesos. The goal is to use CNI combined with Project Calico to handle IP-per-task.

# Build

The `build.sh` script does the following:

* Clones https://github.com/apache/mesos into mesos and builds
* Clones builds https://github.com/projectcalico/calico-cni into cni and builds

# Usage

* Start Zookeeper, Master, Agent and Marathon
* Now deploy the python or nginx app on Marathon

# Question

What do I now have to do in terms of configuration to have Mesos generate an IP via Project Calico?

