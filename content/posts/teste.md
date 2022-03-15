---
title: The Coming of Age for 5G Private Networks
date: 2021-01-05T15:00:00.000+00:00
excerpt: 'This past June, 3GPP completed Release 16, which not only provided support
  for ultra-low latency communications (URLLC) and massive machine-type communications
  (mMTC), but also helped realize another Industrial IoT building block: private networks.
  Private networks are cellular networks used by individual enterprises or other organizations,
  such as police stations or fire departments, and configured for the organization’s
  individual needs. '
img_featured: "/static/images/uploads/group-4357.png"
authors:
- "_authors/rachel-kempf.md"
categories:
- routing-and-networking
- market-trends
description: 'A close look at 5G private networks that examines their value proposition,
  deployment options, business opportunities, and capabilities. '
date_updated: 
og_image: ''
meta_tag_robots_no_index: false

---
This past June, 3GPP completed Release 16, which not only provided support for ultra-low latency communications (URLLC) and massive machine-type communications (mMTC), but also helped realize another Industrial IoT building block: private networks. Private networks are cellular networks used by individual enterprises or other organizations, such as police stations or fire departments, and configured for the organization’s individual needs. As 5G coverage is not yet widely available, giving organizations more control over when and how networks are deployed considerably moves up the timetable for game-changing industrial use cases. Today, we’ll take a close look at private networks by examining their value proposition, deployment options, business opportunities, and capabilities.

## Value Proposition

### The 5 Cs of Private Networks

One concise [explanation](https://www.youtube.com/watch?v=3kDRTuwp5qc) of the value of private networks has been provided by Imran Akbar, VP and GM for Samsung Enterprise. He describes private networks as providing five Cs: coverage, control, capacity, capabilities, and costs.

* Coverage: Small cells can be deployed where organizations need them most. This could include basements, mines, or densely packed areas like stadiums.
* Control: Enterprises can configure their network to ensure quality of service (QoS), use on-site personnel to quickly fix issues, and control how and when their infrastructure is deployed.
* Capacity: Dedicated spectrum and infrastructure allows more capacity as compared to sharing with third parties.
* Capabilities: On-premises networks provide lower latency, can be built for specific purposes, and provide added security with the ability to keep data on location.
* Costs: More control over usage means more predictable operational costs.

Clearly, private networks hold a lot of value for organizations, but as 5G deployments become more widespread, will service providers be able to ensure certain QoS like low-latency and high device density even over public networks? The answer is complex and ultimately dependent on how public networks are deployed.

### 5GC vs. EPC

In our last post, we discussed network slicing, a core architectural principle that enables 5G’s ambitious standards. Network slicing is a way of dividing resources to give operators more granular control over QoS. Vertical slicing creates virtualized private networks for individual enterprises, whereas horizontal slicing divides a network to prioritize critical needs and deliver SLAs. By creating different “slices” for URLLC, mMTC, and eMBB, the different needs of each type of application can be met as efficiently as possible. Certainly this would enable enterprises to gain more capacity and control--that is, assuming networks implement 5G core architecture.

However, 5G core architecture isn’t the only game in town. Current 5G commercial deployments are based on non-standalone architecture (NSA), which uses the evolved packet core (EPC) of LTE networks rather than 5G core, which is entirely cloud-based. Upgrading LTE networks to 5G NSA provides operators more ease and flexibility in deployment, but can’t provide the same degree of control-and-user-plane separation and network slicing as 5G core. This means less granular control and, as a result, lower (and less predictable) QoS. Private networks that are greenfield deployments--i.e. brand-new rather than converted infrastructure--can implement 5G core architecture and reap the benefits that come with it.

## Deployment of Private Networks

### Standalone vs. Integrated Private Networks

5G core (i.e. not integrated with LTE) is often referred to as standalone or SA 5G. This can be confusing however, when discussed in conjunction with private networks, which can be integrated with public networks in varying degrees. 3GPP [explains](https://www.3gpp.org/news-events/2122-tsn_v_lan) the difference between these two basic methods for deploying private networks, also referred to as NPNs (non-public networks):

* Standalone non-public network (SNPN): operated by an NPN operator and not relying on network functions provided by a PLMN; and
* Public network integrated NPN (PNI-NPN): a non-public network deployed with the support of a PLMN.

3GPP’s delineation depends on whether the network is operated privately (standalone NPN) or by a service provider (integrated). In both cases, infrastructure and spectrum is dedicated to the enterprise, but with integrated networks, an enterprise can leverage the support of service providers to avoid the cost and complexity of building and operating its own infrastructure. In addition, another factor may determine whether enterprises decide to contract service providers for operational support: their approach to using spectrum.

### Licensed vs. Unlicensed Spectrum

As discussed in previous posts, one of the key advantages of 5G is that it is able to make use of spectrum bands that can’t be accessed by older networks, resulting in more capacity and higher speed service. 5G NR is capable of connecting to low-, mid-, and high-band (or mmWave) spectrum, allowing it to deliver wider coverage through lower bands as well as higher capacity and speed through higher bands.

Although some countries may set aside licensed spectrum for use in various industries, most countries auction spectrum to service providers, who may, in turn, sub-license spectrum to enterprises for private use. However, with Release 16, 5G now supports the use of unlicensed spectrum, or NR U, which can either be used exclusively or anchored to licensed spectrum.

In contrast to licensed spectrum, which can only be used by the company that purchased it, unlicensed spectrum can be used by anyone. As noted in a [recent GSMA white paper](https://www.gsma.com/iot/wp-content/uploads/2020/10/2020-10-GSMA-5G-IoT-Private-and-Dedicated-Networks-for-Industry-4.0.pdf), this avoids the many regulations governing licensed spectrum use, such as interference avoidance and electromagnetic field limits, making the standalone operation of private networks easier for enterprises who are not well-versed in navigating these regulations. However, these networks would be more subject to interference (for example, from WiFi) and less capable of ensuring QoS; in addition, some countries may only make certain frequencies available for unlicensed use, resulting in more limited capabilities if NR U is not anchored to licensed spectrum.

## The Business of Private Networks

### Metrics

Even before Release 16 provided support for industrial IoT and NPNs, Gartner predicted a significant need for 5G private networks. A [2018 Gartner report](https://www.gartner.com/en/newsroom/press-releases/2018-12-18-gartner-survey-reveals-two-thirds-of-organizations-in) noted that while 66% of organizations claimed they plan to deploy 5G by 2020, service providers were not on track to amass the radio density, network slicing and edge computing infrastructure required for enterprise use cases. “Their 5G networks are not available or capable enough for the needs of organizations,” said Sylvain Fabre, senior research director at Gartner. “Private networks for enterprises will be the most direct option for businesses that want to benefit from 5G capabilities early on.”

As a result, enterprises are expected to invest heavily in private networks over the next few years. A [2019 Deloitte article](https://www2.deloitte.com/us/en/insights/industry/technology/technology-media-and-telecom-predictions/2020/private-5g-networks.html#endnote-sup-2) forecasted that by the end of 2020, over 100 companies across the world will have tested private network deployments, spending millions of dollars on labor and equipment for private networks. By 2024, they estimate that number will balloon to tens of billions of dollars _each year._ Ports, airports, and other logistic hubs are expected to adopt private networks first, comprising a third of private networks in the first five years. Another third will likely come from factories and warehouses, with greenfield deployments such as college campuses making up the final third.

### Reinventing Business Operations

The limited capabilities of previous technologies meant that enterprises may need to deploy a mixture of Ethernet, WiFi, and cellular technology to gain wide coverage and high performance. This results in a complex mix of wires, cables, and other equipment that can be difficult to deploy and maintain. 5G not only provides superior performance than older networks, but removes the physical constraints of cables and wires and provides connectivity in places where WiFi isn’t practical.

This not only provides new business opportunities through URLLC and mMTC use cases, but enables new ways of conducting business. Through the use of 5G, organizations can:

* Operate in environments filled with metal
* Prioritize different services through network slicing
* Make equipment more mobile
* Automate more processes
* Connect more devices
* Avoid the cost of maintaining wires and cables
* Reduce downtime for reconfiguring or repairing production lines

[Deloitte](https://www2.deloitte.com/us/en/insights/industry/technology/technology-media-and-telecom-predictions/2020/private-5g-networks.html#endnote-sup-2) provides two examples of this kind of “process reinvention” in manufacturing. Most of today’s factory lines are fixed, limiting the ability for modular assembly and creating bottlenecks where assembly is slow or repairs need to be completed. By taking advantage of 5G, Mercedes TecLine has been able to customize assembly with mobile devices that carry cars from one part of the factory to another and use an intelligent system to choose specified parts. In China, Bosch Rexroth is building an even more modular assembly line with a completely mobile factory powered by autonomous machines that can be deployed and reconfigured as needed.

## Release 16 Capabilities

In addition to enabling private 5G networks and unlicensed spectrum use, Release 16 provides a number of technical capabilities that enable industrial use. A recent [Qualcomm article](https://www.qualcomm.com/news/onq/2020/07/07/propelling-5g-forward-closer-look-3gpp-release-16) provides a detailed list of these improvements, which can be briefly summarized as:

* Power-saving features to improve battery life for mMTC
* MIMO improvements to enable more users and better link reliability
* Improved reliability for URLLC through redundant communication paths
* IAB (integrated access backhaul), which eliminates the need for wired backhaul
* TSN (time sensitive networking) for precisely timed delivery of data packets
* C-V2X (cellular vehicle to everything), allowing cars to connect to pedestrians and each other

Through these technical improvements and the business opportunities of private networks and unlicensed spectrum, Release 16 provided the foundation for industrial use of 5G, enabling new use cases across a variety of industries.

## Conclusion

The ability to create private 5G networks will not only accelerate the adoption of 5G, but provide enterprises and other organizations operational, logistic, and performance-based benefits. Much like public networks, however, private networks will need edge computing to maximize their capabilities, particularly with regards to latency. Using our software license, customers can run Azion on their own premises, bringing data processing closer to devices and enabling more automation. With Edge Functions, clients can program customized or ready-to-use functions that execute in response to events, while Edge Orchestrator provides the ability to automate, control, and manage resources in real time. Furthermore, Azion is built for interoperability and able to run on a variety of microprocessor architectures, equipment sizes, and network equipment.
