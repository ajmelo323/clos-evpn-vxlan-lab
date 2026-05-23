# LinkedIn Project Description

## Project Title

EVPN/VXLAN Clos Fabric Lab using Containerlab + FRRouting

## Short Description

Built a Linux-based Clos fabric using Containerlab and FRRouting inside an Ubuntu VM to better understand hyperscale leaf/spine architectures, eBGP underlays, EVPN overlays, and VXLAN-based network virtualization concepts.

## Longer Description

This project uses a 2-spine / 3-leaf topology with FRRouting containers deployed through Containerlab. The lab validates a multi-AS eBGP underlay between spine and leaf nodes and includes EVPN overlay configuration on the leaf VTEPs using VNI 100 with route-target import/export policies.

The project helped reinforce modern data center networking concepts such as routed Clos fabrics, BGP-based underlays, EVPN control-plane configuration, VTEP placement, and Linux-based network virtualization workflows.

## Message To Send

Absolutely — I cleaned the lab up and pushed the topology, configs, screenshots, and notes into a GitHub repo. It is a Containerlab + FRRouting based Clos fabric running inside Ubuntu with an eBGP underlay and EVPN overlay configuration on the leaf VTEPs.

Still refining the VXLAN dataplane and MAC advertisement side, but the lab has been a strong hands-on project for understanding hyperscale leaf/spine architecture, EVPN signaling, and Linux-based network virtualization.
