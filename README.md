# Lab Status Notes

## What Was Validated

This lab successfully validated the eBGP underlay across a 2-spine / 3-leaf Clos fabric using Containerlab and FRRouting.

Validated items:

- Containerlab deployment
- FRR containers running
- Spine/leaf point-to-point interfaces created after redeploy
- eBGP sessions established between spine and leaf nodes
- Prefix exchange across the fabric
- EVPN address-family configured
- VNI 100 and route-target import/export configured on leaf nodes

## Important Technical Note

The EVPN configuration is present on the leaf nodes because the leaf nodes represent the VTEP role in the design.

The spines are used for routed fabric transport and BGP participation. The VNI-specific EVPN configuration is intentionally shown on the leaves, not the spines.

## Current Limitation

`show bgp l2vpn evpn` did not show EVPN prefixes during validation because the VXLAN dataplane and MAC/IP advertisement components still need to be fully completed.

This is documented honestly as a future improvement.
