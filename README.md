# Enhancing Network Insights: SDN Monitoring on FABRIC

This [python notebook](https://github.com/bindrad/SDN-Monitoring-on-FABRIC/blob/main/monitoring/monitoring.ipynb) was cloned from Fabric's knowledge base on [MfLib](https://github.com/fabric-testbed/jupyter-examples/tree/main/fabric_examples/mflib).
The configuration of prometheus was modified based on the requirements to push the metrics to all the nodes in the network. The used prometheus configuration is attached at the last of the notebook.

The initial attempt to implement congestion control based on ECN using P4 is in [congestion_control directory](https://github.com/bindrad/SDN-Monitoring-on-FABRIC/blob/main/congestion_control/ecn.p4).