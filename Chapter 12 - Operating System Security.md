LOOK ON SLIDES
## Strategies
- Top 4 strategies for prevention:
	- White-list approved applications
	- Patch third-party applications and operating system vulnerabilities
	- Restrict administrative privileges
	- Create a defense-in-depth system

## Operating System Security
- Possible for system to be compromised during installation process before it can install latest patches
- Building an deploying a system should be a planned process designed to counter this threat
- Process must:
	- Asses risks and plan the system deployment
	- Secure underlying operating system and then the key applications
	- Ensure any critical content is secured
	- Ensure appropriate network protection mechanisms are used
	- Ensure appropriate processes are used to maintain security

##  System Security Planning
- First step in deploying a new system is planning
- Plan needs to identify appropriate personnel and training to install and manage the system
- Planning should include a wide security assessment of the organization
- Planning process needs to determine security requirements for the system, applications, data, and users
- Aim is to maximize security while minimizing costs

## System Security Planning Process
- Purpose of system
- Categories of users, privileges, types of info accessible
- How users authenticated
- How access information stoer on system is managed
- What access system has to information stored on other hosts (ex: databases)
- Who will administer system and how will manage (local or remote access)
- Any additional security measures require don system, including use of host firewalls, anti-virus, or other malware protection mechanisms, and logging

## Operating Systems Hardening
- First critical step in securing a system is to secure the base operating system
- Basic steps
	- Install and patch (update) operating system
	- Harden and configure the operating system to adequately address the identified security needs of the system by:
		- Removing unnecessary services, applications, and protocols
		- Configuring users, groups, and permissions
		- Configuring resource controls
	- Install and configure additional security controls, such as anti-virus, host-based firewalls, and intrusion detection system (IDS)
	- Test security of basic operating system to ensure that steps taken adequately address its security needs

## Initial Setup and Patching
- protected network
- Install patch right away
- Full installation before system put to work
- Keep it updated

## Remove Unnecessary Services, Applications, and Protocols
- If fewer software packages available, to run the risk si reduced
- System planning process should identify what is actually required for given system
- When performing the initial installation the supplied defaults should not be used
	- Default configuration is set to maximize ease of use and functionality rather than security
	- If additional packages are needed later they can be installed when they are required
- Default configuration
	- Made for ease of use
		- NOT meant for security
	- Avoid using it

## Configure Users, Groups, and Authentication
- Not all users with access to system will have same access to all data and resources on that system
- Elevated privileges should be restricted to only those users that require them, and then only when they are needed to perform a task
- System planning process should consider:
	- Categories of users on system
	- Privileges they have
	- Types of information they can access
	- How and where they are defined and authenticated
- Default accounts included as part of system installation should be secured
	- Those that are not required should be removed or LOOK ON SLIDES

## Configure Resource Controls and Install Additional Security Controls
- LOOK ON SLIDES

## Test System Security
- Programs that find known vulnerabilities or poor configurations and it would flag them
	- Should be done after OS is hardened

## Application Configuration
- May include:
	- Creating / Specifiying appropriate data storage for application
	- Making appropriate changes to applicaiton or service default configuration details
- Some applications or services amy include:
	- Default data
	- Scripts
	- User accounts
- Of particular concern with remotely accessed services such as Web and file transfer services
	- Risk form this form of attack is reduced by ensuring that most of the files can only be read, but not written, by the server

## Encryption Technology
- Is a key enabling technology that may be used ot secure data both in transit and when stored
- Must be configured and appropriate cyrptographic keys created, signed, and secured
- If secure network services are provided usign TLS or IPsec suitable pulbic and private keys must be generated for each of tehm
- If secure network services provided using SSH, LOOK ON SLIDES

## Security Maintenance
- Includes:
	- Monitory the logs
	- Preform regular backups of file or system
	- Test system regularly 
	- --------------------------------
	- Logging
		- Do not prevent attacks, but helps identify core reason
	- Data Backups

## Logging
- Can only inform about bad things that have already happened
- Allows to quickly identify what happened
- Key ensures capture correct data and then monitor and analyze data
- Information generated by system, network and applications
- LOOK ON SLIDES

## Data Backup and Archive
- Backup:
	- process of makign copies of data at regular intervals
	- Process of making copies of data at regular tome nterval
- Archive
	- Process of retaining copies of data
- Needs policy relating to backup and archive sohuld be determiend during system plannign stage
	- Kept online or offline
	- Stored locally or LOOK ON SLIDES

## Linux/Umix Security
_Shoosh Slides LOOK ON SLIDES

## Windwos Security 
- USers Adminratiob andd success
- Windows also auto protivimeges
- LOOK ON SLIDES
- Applications and Service Configration
- Must of reistery feail
- LOOK ON SLIDES

# Virtualization
- Tech provided abstration of resourced used by some virtual machine that runs it
- Benefits: suppport fro mikoka operatin 
- Better efficiency'Support for multiple distinc operatin gsytems 
- Provide support for multple dinstnce  
- Virtual Machines
	- Type-1 Bare Metal ???????

## Hypervisor Fun Far
- Principal funcions performed by haypervisor area;
	- Execution amanagement of VMs
-'LOOK ON SLIDES

## Containers
- Share host machine

## Containers vs Virtualizaiton
- Virtualization:
	- Room within room
- Containers
	- Room sharing another room

## Virtualization Security Issues
- Includes:
	- Guest OS isolation
		- Ensuring programs executing with giest is OS may only access and use resources allocated to it
	- Guest OS monitoring by hypervisor
		- Which has privileged access to programs and data in each guest OS
	- Virtualized environment security
		- Particularly image and snapshot management which attackers may attempt to view or modify

## Securing Virtualization Systems
- Organizations using virtualization should:
	- Carefully plan the security of teh virtualized system
	- Secure all elements of a full virtualization solution and maintain security
	- Ensure hypervisor is properly secured
	- Restrict and protect administrator access to virtualization solution

## Hypervisor Security
- Should be
	- Secured using process similar to securing an operating system
	- Installed in isolated environment
	- Configured so that is updated automatically
	- Monitored for any signs of compromise
	- Accessed only by authorized administration
- May support both local and remote administration so must be configured appropriatley

## Virtual Firewall
- Provides firewall capabiliteis for network traffic flowing between systems hosted in virtualized or cloud environment that does not require traffic to be routed to a physically separate network
- LOOK ON SLIDES

