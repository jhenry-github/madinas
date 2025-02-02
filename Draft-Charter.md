#### Charter of Working Group
##### The Medium Access Control (MAC) address is the Link Layer address typically used in IEEE 802 technologies. It is usually assigned statically for each network card by the Network Interface Card manufacturer, out of the space reserved for globally unique MAC addresses, and it is used for sending and receiving frames. The default static assignment of the MAC address raises privacy concerns, which have recently started to be mitigated by new specifications such as IEEE 802.11aq, and end-device OSs implementing MAC address randomization.

##### Currently, many use cases and applications make an implicit assumption of the unique association between the device identity and its MAC address. This assumption is being used in both control plane and data plane. Device identity is important in scenarios where the network needs to know the device before offering services. Randomized and Changing MAC address (RCM) will break this assumption. This requires update of the current applications to function across MAC address changes.

##### The MADINAS Working Group will examine the effect of RCM schemes on network services in several scenarios previously identified as relevant. The group will examine how client MAC address changes can affect services continuity. The group will also explore which identifiers (beyond the MAC address) can be used by the network to provide services.

##### For scenarios where session continuity is desirable, the Working Group will explore improvements to protect the exchange of identifiers between the client and the service provider. For scenarios where privacy is paramount, the group will recommend best practices to ensure that the privacy achieved with RCM rotation is not damaged by the communication of other stable identifiers. The MADINAS Working Group will examine the applicability of other existing IETF work, preserving the end-user privacy, that can be applied to mitigate the problems created by the use of RCM schemes.

##### The Working Group will liaise with other IETF WGs, and relevant SDOs such as IEEE 802 and the WBA, to coordinate on the different recommendations resulting from this work, as well as potential follow-up activities within or outside the IETF.

##### MADINAS is expected to be a short timeframe (12-18 months) Working Group to quickly address these needs. The initial milestones will only include Informational documents: Problem Statement (including use cases and requirements), MAC Address Randomization analysis, and BCP. Additional solution space documents may be published after a rechartering process, if this is identified as necessary, and it would be done in coordination with other relevant SDOs.

##### Milestones:
- Working Group adoption of Problem Statement document, including use cases analysis and requirements.
- Working Group adoption of MAC Address Randomization analysis document.
- Problem Statement document submitted to IESG.
- MAC Address Randomization analysis document submitted to IESG.
- Working Group adoption of Recommendations and Best Practices document.
- Recommendations and Best Practices document submitted to IESG.

