Operational technology (OT) is hardware and software that detects or causes a change, through the direct monitoring and/or control of industrial equipment, assets, processes and events.
The term has become established to demonstrate the technological and functional differences between traditional information technology (IT) systems and industrial control systems environment, the so-called "IT in the non-carpeted areas".

Examples
Examples of operational technology include:

Programmable logic controllers (PLCs)
Supervisory control and data acquisition systems (SCADA)
Distributed control systems (DCS)
Computer numerical control (CNC) systems, including computerized machine tools
Scientific equipment (e.g. digital oscilloscopes)
Building Management System (BMS) and building automation systems (BAS)
Lighting controls both for internal and external applications
Energy monitoring, security and safety systems for the built environment
Transportation systems for the built environment
Technology
The term usually describes environments containing industrial control systems (ICS), such as supervisory control and data acquisition (SCADA) systems, distributed control system (DCS), remote terminal units (RTU) and programmable logic controllers (PLC), as well as dedicated networks and organization units. The built environment, whether commercial or domestic, is increasingly controlled and monitored via 10s, 100s, and 1,000s of Internet of Things (IoT) devices. In this application space, these IoT devices are both interconnected via converged technology edge IoT platforms and or via "cloud" based applications. Embedded Systems are also included in the sphere of operational technology (e.g. smart instrumentation), along with a large subset of scientific data acquisition, control, and computing devices. An OT device could be as small as the engine control unit (ECU) of a car or as large as the distributed control network for a national electricity grid.

Systems
Systems that process operational data (including electronic, telecommunications, computer systems and technical components) are included under the term operational technology.
OT systems can be required to control valves, engines, conveyors and other machines to regulate various process values, such as temperature, pressure, flow, and to monitor them to prevent hazardous conditions. OT systems use various technologies for hardware design and communications protocols, that are unknown in IT. Common problems include supporting legacy systems & devices and numerous vendor architectures and standards.
Since OT systems often supervise industrial processes, most of the time availability must be sustained. This often means that real time (or near-real time) processing is required, with high rates of reliability and availability.
Laboratory systems (heterogenous Instruments with embedded computer systems or often non standardized technical components used in their computer systems) are commonly a borderline case between IT and OT since they mostly clearly don't fit into standard IT scope but also are often not part of OT core definitions. This kind of environment may also be referred to as industrial information technology (IIT).

Protocols
Historical OT networks utilized proprietary protocols optimized for the required functions, some of which have become adopted as 'standard' industrial communications protocols (e.g. DNP3, Modbus, Profibus, LonWorks, DALI, BACnet, KNX, EnOcean and OPC-UA). More recently IT-standard network protocols are being implemented in OT devices and systems to reduce complexity and increase compatibility with more traditional IT hardware (e.g. TCP/IP); this however has had a demonstrable reduction in security for OT systems, which in the past have relied on air gaps and the inability to run PC-based malware (see Stuxnet for a well-known example of this change).

Origins
The term operational technology as applied to industrial control systems was first published in a research paper from Gartner in May 2006 (Steenstrup, Sumic, Spiers, Williams) and presented publicly in September 2006 at the Gartner Energy and Utilities IT Summit.[2] Initially the term was applied to power utility control systems, but over time was adopted by other industrial sectors and used in combination with IoT.[3] A principal driver of the adoption of the term was that the nature of operational technology platforms had evolved from bespoke proprietary systems to complex software portfolios that rely on IT infrastructure. This change was termed IT OT convergence.[4] The concept of aligning and integrating the IT and OT systems of industrial companies gained importance as companies realized that physical assets and infrastructure was both managed by OT systems but also generated data for the IT systems running the business. In May 2009 a paper was presented at the 4th World Congress on Engineering Asset Management Athens, Greece outlining the importance of this in the area of asset management [5]
Industrial technology companies such as GE, Hitachi, Honeywell, Siemens, ABB and Rockwell are the main providers of OT platforms and systems either embedded in equipment or added to them for control, management and monitoring. These industrial technology companies have needed to evolve into software companies rather than being strictly machine providers. This change impacts their business models which are still evolving [6]

Security
From the very beginning security of operational technology has relied almost entirely on the standalone nature of OT installations, security by obscurity. At least since 2005 OT systems have become linked to IT systems with the corporate goal of widening an organization's ability to monitor and adjust its OT systems, which has introduced massive challenges in securing them.[7] Approaches known from regular IT are usually replaced or redesigned to align with the OT environment. OT has different priorities and a different infrastructure to protect when compared with IT; typically IT systems are designed around 'Confidentiality, Integrity, Availability' (i.e. keep information safe and correct before allowing a user to access it) whereas OT systems require 'realtime control and functionality change flexibility, availability, integrity, confidentiality' to operate effectively (i.e. present the user with information wherever possible and worry about correctness or confidentiality after).

Other challenges affecting the security of OT systems include:

OT components are often built without basic IT security requirements being factored in, aiming instead at achieving functional goals. These components may be insecure by design and vulnerable to cyber-attacks.
Vendor dependency: Due to the general lack of knowledge related to industrial automation, most companies are heavily dependent on their OT vendors. This leads to vendor lock-in, eroding the ability to implement security fixes.
Critical assets: Because of OT's role in monitoring and controlling critical industrial process, OT systems are very often part of national critical infrastructures. As such they may require enhanced security features as a result.
Common vulnerabilities
OT often control and monitor important industrial processes, critical infrastructure, and other physical devices. These networks are vital for the proper functioning of various industries, such as manufacturing, power generation, transportation and our society. Most common vulnerabilities and attack vectors should be addressed, whereof :

Legacy systems and outdated technology: Many OT networks still rely on older hardware and software that may not have been designed with security in mind, making them more susceptible to cyber attacks.
Lack of segmentation: Inadequate network segmentation can lead to a compromised device in one part of the network, which may allow an attacker to access other parts of the network, increasing the overall risk.
Insufficient authentication and access control: Weak authentication mechanisms and access controls can enable unauthorized users to gain access to sensitive systems and data.
Insecure communication protocols: Many OT networks use proprietary or legacy communication protocols, which may lack encryption or other security features, making them vulnerable to eavesdropping and data tampering.
Limited visibility and monitoring: OT networks often lack comprehensive monitoring and visibility tools, which makes it difficult to detect and respond to potential security incidents.
Insider threats: Malicious insiders or negligent employees can exploit their access to OT networks to cause harm or steal sensitive data.
Integration with IT networks: The increasing convergence of IT and OT networks can introduce new vulnerabilities and attack vectors, as vulnerabilities in one network can potentially be exploited to compromise the other.
Supply chain risks: Compromised hardware or software components in the OT network can introduce vulnerabilities that attackers can exploit.
Physical security: OT networks involve physical devices and infrastructure that can be susceptible to physical attacks, such as tampering or theft.
Lack of cybersecurity awareness and training: Many organizations do not adequately train their employees on the importance of cybersecurity, leading to an increased risk of human error and insider threats.
To protect against these risks, organizations should adopt a proactive, multi-layered security approach, including regular risk assessments, network segmentation, strong authentication, and access controls, as well as continuous monitoring and incident response capabilities.

Critical infrastructure
Operational technology is widely used in refineries, power plants, nuclear plants, etc. and as such has become a common, crucial element of critical infrastructure systems. Depending on the country there are increasing legal obligations for Critical Infrastructure operators with regards to the implementation of OT systems. In addition certainly since 2000, 100,000's of buildings have had IoT building management, automation and smart lighting control solutions fitted [8] These solutions have either no proper security or very inadequate security capabilities either designed in or applied.[9] This has recently led to bad actors exploiting such solutions' vulnerabilities with ransomware attacks causing system lock outs, operational failures exposing businesses operating in such buildings to the immense risks to health and safety, operations, brand reputation and financial damage [10]

Governance
There is a strong focus put on subjects like IT/OT cooperation or IT/OT alignment [11] in the modern industrial setting. It is crucial for the companies to build close cooperation between IT and OT departments, resulting in increased effectiveness in many areas of OT and IT systems alike (such as change management, incident management and security standards) [12] [13]

A typical restriction is the refusal to allow OT systems to perform safety functions (particularly in the nuclear environment), instead relying on hard-wired control systems to perform such functions; this decision stems from the widely recognized issue with substantiating software (e.g. code may perform marginally differently once compiled). The Stuxnet malware is one example of this, highlighting the potential for disaster should a safety system become infected with malware (whether targeted at that system or accidentally infected).

Sectors
Operational technology is utilized in many sectors and environments, such as:

Oil and gas
Power and utilities
Chemicals manufacturing
Water treatment
Waste management
Transportation
Scientific experimentation
Critical manufacturing
Building management and automation
Building lighting controls and automation
Mining and mineral processing
