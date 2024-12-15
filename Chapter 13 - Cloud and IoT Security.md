## Cloud Computing
- Cloud Computer: model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction. This cloud model promotes availability and is composed of five essential characteristics, three service models, and four deployment models

## Cloud Service Models
- Three service models (ca be viewed as nested service alternatives)
	- Software as a services (Saas)
		- They manage security, storage, antivirus, etc
	- Platform as a service (PaaS)
		- LOOK ON SLIDES
		- Deploy server/device on cloud
	- Infrastructure as a service (IaaS)
		- Customer has access to cloud structure

## Cloud Deployment Modukles
 - 4 deployment problems

## Public Cloud
- Made available to generla public ro large industry group and owned by organization saelling closue services
- Public cloud may ne owned, managed, and operated by a business, academic, or governmentorganizaitionm or some combination of them
- Private clouse is implemented within Iternal IT environmnet of thje organization
- Requiereed more maintance

## Private Cloud
- Implimented within IT of organization
## Community Cloud
- A community cloud shares characteristics of private and public clouds
	- Has restricted access like a private cloud
	- The cloud resources are shared among a number of independent organizations like a public cloud

## Hybrid
- The hybrid cloud infrastructure is a composition of two or more clouds (private, community, or public) that remain unique entities but are bound together by standardized or proprietary technology that enables data and application portability
- With a hybrid cloud solution, sensitive information can be placed in a private area of the cloud, and less sensitive data can take advantage of the benefits  of the public cloud

## LOOK ON SLIDES

## Guidelines on Cloud Security and privcy Issues and Recommendations
- Governance
	- Best practices / guide on policies, procedures, standards used for development and using cloud
- Compliance
	- Understand legal requirements for data security
		- Ex: Cloud provider follows compliance rules to store a company's information in a specific place
- Trust
	- Trust Factor
		- Cloud company assuance on security
			- Aka, they tell who is responsible for data security, etc...
- Architecture
	- "Knowing the layout of the building"
	- Organization using Cloud provider services can know how secure their data is, the faults, etc...
- Identity and Access Management
	- Ensures secure authentication and authorization for users
		- Only people with that privilege can accesses the resource
- Software Isolation
	- Virtualization, logical isolation, etc...
- Data protection
	- Have to secure information on the cloud
- Availability
	- Guidelines to data backup, data recovery
	- Runs smoothly during emergencies
- Incident response
	- Organizations respond quickly
	- Emergency response plan

## Security Issues for Cloud Computing
- Still plenty of security issues

## Risks and Countermeasures
- LOOK ON SLIDES FOR ALL OF THESE! THEY HAVE MORE EXAMPLES!
- Abuse and nefarious use of cloud computing
	- Countermeasures include:
		- stricter validation
		- inspection of custom network traffic
- Insecure interfaces and APIs
	- Countermeasures include:
		- Analyzing the security model of CSP interfaces
		- Ensuring that strong authentication and access controls are implemented in concert with encrypted transmission
- Malicious insiders
	- Countermeasures include:
		- Enforce strict supply chain management and conduct a comprehensive supplier assessment
		- Determine security breach notification processes
- Shared technology issues
	- Countermeasures include:
		- Implement security best practices for installation/configuration
		- Monitor environment for unauthorized changes/activities
- Data loss or leakage
	- Countermeasures include:
		- Implement strong API access control
		- Encrypt and protect integrity of data in transit and at rest
- Account or service hijacking
	- Countermeasures include:
		- Prohibit the sharing of account credentials between users and services
		- Leverage strong two-factor authentication
- Unknown risk profile
	- Countermeasures include:
		- Disclosure of applicable logs and data
		- Partial/full disclosure of infrastructure details
		- Monitoring and alerting on necessary information

## Data Protection in the Cloud
- Encrypting data, controlled access, key management
- Multi-instance Model
	- Provides a unique DBMS running on a VM instance for each cloud subscriber
	- This gives the subscriber complete contorl over role definition, user authorization, and other administrative tasks related to security
- Multi-tenant Model
	- Provides a predefined environment for the cloud subscriber that is shared with other tenants, typically through tagging data with a subscriber identifier
	- Tagging gives teh appearance of exclusive use of the instance, but relies on teh cloud provider to establish and maintain a sound secure database environment
## Cloud Security as a Service
- CSA defines SecaaS categoreis of service

## OpenStack
- Open-source software project to produce open-source cloud operating system
- Security module for OpenStack is Keystone
- Keystone provides shared security services essential for functioning cloud computing infrastructure
	- Provides following main services:
		- Identity
		- Token
		- Service Catalog
		- Policies

## The Internet of Things (IoT)
- Refers to expanding interconnection of smart devices, ranging from appliances to tiny sensors
- Objects deliver sensor information, act on their environment, and in some cases modify themselves, to create overall management of a larger system

## Evolution
- Internet gone through 4 generations of deployment culminating in the IoT
- Information technology (IT)
	- PCs, servers, routers, firewalls, etc...
- Operation technology (OT)
	- Machines/appliances embedded IT build by non-IT companies like, medical machinery
- Personal technology
	- Phones, etc...
- Sensor/acuateor technologies
	- Single-purpose devices bought by consumers, IT and OT people exclusively using wireless connectivity (ex: Alexa), generally of a single form ,as part of larger systems
- Fourth generation usually thought of IoT

## IoT Components
- Sensors
	- Detects change
- Actuator:
	- Component that acts on a signal received
- Microcontroller:
	- Brain of the system
- Transiters
	- Module by infacieneoten

## IoT part in cloud
- Same thing but used in the cloud

## Edge
- At the edge of a typical enterprise network is a network of IoT-enabled devices consisting of sensors and perhaps actuators
	- Devices may communicate with one another
	- Clusters of sensors may all tranasmit their data to one sensor that aggregates the data to be collected by a higher-level entity
- A **gateway** interconnects the IoT-enabled devices witht eh higher-level communciation entworks
	- It performs the necessary translation between the protocols iused int eh communicatino networks ans dthose used by devices
	- May also perform a basic data aggregation function

## Fog
- In many IoT deployments, massive amounts of data may be generated by a distributed network of esnsors.
- Rhater than astore all that data permanenetly in central storage that IoT apps can use, it is often desirable to do as m uch data processing close to sensors as possible
- Purpose of what is refferred to as edge computing level is to convert network data flows into information that is suitable for storage and higher-level processing
- Processing elements at these levelsmay deal with high volumes of data and perform data transformation operations, resulting int eh storage of much lower volumes of data
- Following are examples of fog computing operations:
	- Evaluation
	- Formatting
	- Expanding/decoding
	- Distillation/reduction
	- Assesssment

## Fog vs Cloud
- LOOK IT UP

## Fog Cont.
- LOOK ON SLIDES
- Addresses challenges raised by activity of thousands or millions of smart devices

## Core
- Core network, aslo referred to as backbone network, connects geographically disperesed fog networks as well as providing access to otehr networks that are not enterprise network
- LOOK ON SLIDES

## Comparison of Cloud and Fog Features

|     | Cloud                                  | Fog                     |
| --- | -------------------------------------- | ----------------------- |
|     | Center                                 | Edge                    |
|     | High                                   | Low                     |
|     | Fixed or Wireless                      | Mainly Wireless         |
|     | Not applicable                         | Yes                     |
|     | Centralized/hierachical (full control) | Distributed/heiarchical |
- # LOOK ON SLIDE TO COMPLETE THE TABLE

## Patching Vulnerability
- Crisis point with regard to security of embedded systems, including IoT devices
- Embedded devices riddled with vulnerabiltiies and no good way to patch them
- Chip manufactures do not prioritize securtity
	- Only care about producing quickly and as cheaply as possible
- Device manufacturs focus on functionality of device itself
- ENd user may have no mean sof patching system or have too little info about when and how to patch
- Result is hundreds of millions of internet-connected devices in IoT are vulnerable to attack
- Thhis is certainly a problem with sesnors, allowing attackers to insert false data into the network
- Potentially agraver threat with actuators, where attacker can affect operation of machinery and devices

## IoT Security and Privacy Requirements
- Requirements defined as being functional requirements during capturing, storingm transferring, aggregatingm and processing data of things, as well to provision of services which involve things
- Requirements arae:
	- Communication Security
		- Securely move data
	- Data management Security
		- Data is secured
	- # LOOK ON SLIDES FOR OTHER 7

## MiniSec
- Open-source security module that is part of the TinyOS operating system
- It is designed to be a link-level module that offers high level of security while simultaneously keeping energy consumption low and using very little memory
- MiniSec provides confidentiality, authentication, and replay protection
- MinSec has two operating modes, one tailored for single-source communication, and another tailored for multi-source broadcast communication
- Designed to meet following requirements:
	- Data authentication
	- Confidentiality
	- Replay protection
	- Freshness
	- # LOOK ON SLIDE FOR FRESHNESS AND 2 MORE

