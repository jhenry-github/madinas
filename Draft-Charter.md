#### Charter of Working Group
##### The Medium Access Control (MAC) address is the Link Layer address used in IEEE 802 technologies. It is usually assigned statically for each physical network card by the Network Interface Card manufacturer, out of the space reserved by the IEEE Registration Authority Committee (RAC) for globally unique MAC addresses. The MAC address is used as source or destination target when sending and receiving frames. The default static assignment of the MAC address raises privacy concerns for personal devices, which have recently started to be mitigated by end-device vendors implementing and SDOs specifying the use of Randomized and Changing MAC addresses (RCM).

##### Device identity is important in scenarios where the network needs to know the device or user identity in order to offer, operate and maintain certain services. Currently, many use cases and applications make an implicit assumption about the unique association between the device identity and its MAC address. This assumption is being used in both control plane and data plane functions and protocols. RCM will break this assumption. This requires update of the current applications to function across MAC address changes.

##### The MADINAS Working Group will examine the effect of RCM schemes on network and application services in several scenarios identified as relevant. The group will also evaluate various identifiers (beyond the MAC address) that can be used by the network to provide services, as well as scenarios where personal device identity is not required.

##### For scenarios where personal device identity stability is desirable, the Working Group will recommend protocols that can be used to protect the request and exchange of identifiers between the client and the service provider. For scenarios where privacy is paramount, the group will recommend best practices to ensure that the privacy achieved with RCM is not compromised by the communication of other identifiers. The MADINAS Working Group will examine other IETF work that may be applicable.

##### The Working Group will work together with other IETF WGs (e.g., DHC, intarea), and will liaise with other relevant SDOs such as IEEE 802 and the Wireless Broadband Alliance (WBA). The Working Group will coordinate on the different recommendations, as well as potential follow-up activities within or outside the IETF.

##### MADINAS is expected to be a short timeframe (12-18 months) Working Group to quickly assess these needs. Additional solution space documents may be published after a rechartering process is identified as necessary and in coordination with other relevant SDOs.

##### Milestones:
- Working Group adoption of Problem Statement document, including use cases analysis and requirements.
- Working Group adoption of MAC Address Randomization analysis document.
- Problem Statement document submitted to IESG.
- MAC Address Randomization analysis document submitted to IESG.
- Working Group adoption of Recommendations and Best Practices document.
- Recommendations and Best Practices document submitted to IESG.

