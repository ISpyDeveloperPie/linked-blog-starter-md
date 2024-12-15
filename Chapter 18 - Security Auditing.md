- Security Auditing
	- Review and examination of a system records and activities
	- Provides organization (Ex: security quota, where do they stand in security, what potential threats are out there)
	- Checks if everything is functioning as it should
	- Gives recommendations
	- Establish accountabiltiy that system is working as expected
- Security Audit Trial
	- Chronological record of activity that can recreate the procedures for an operation
	- Events that can reconstruct an environment of what is supposed to happen and find out if something went wrong or right
	- Used to examine the situation

## Event Security and Alarms
- # LOOK ON SLIDES FOR GRAPH
- Event discriminator
	- Detects actions
- Alarm Processor
	- Does action based on event discriminator
- Audit Recorder
	- Record / Creates logs for audit trial
- Security Audit Trial
	- Uses resources given by Audit Recorder
- Audit Provider
	- Provides audit trials
- Audit Archiver
	- records audit
- Audit Trail Examiner
	- All of analysis are recorded
- Security Reports
	- Gets result from Audit Trial Examiner and makes report

## Event Definition
- Must defines that set of events that are subject to audit
- Common criteria suggests:
	- Introduction of objects
	- Deletion of objects
	- Distribution or revocation of access rights or capabilities
	- Changes to subject or object security attributes
	- etc (look on slides)

## Event Detection
- Appropriate hooks must be on system to do event detection
- Monitoring software to capture relavent data
- Secure event recording function
- Event and audit trial analysis software

## Implementation Guidelines
- Agree on audit requirements with appropriate management
- Audit tests limited to read-only
	- Access other than read-only should be isolated
- look on slides

## What to collect
- Events related to use of auditing software
- Events related to security mechanisms on the system
- Operating System Access
- Look on slides
- Remote Access

## Auditable Items Suggest in X.8???
- LOOK ON SLIDES

## Physical Access Audit Trials
- Generated by equipment that controls physical access
	- Card-key systems, alarm systems
- Sent to central host for analysis or change
- LOOK ON SLIDES

## Protecting Audit Trial Data
- Basically logging
- Read/write file on host
- write-once/read-many device
- Write-only device
- Must protect both Confidentiality and Integrity
- ## LOOK ON SLIDES

## Implementing Logging
- Foundation of security auditing facility is the initial capture of the audit data
- Software must include hooks (capture points) that trigger data collection and storage 
- look on slides

## Windows Event Log
- Event is an entity that describes some interesting occurrence
	- Contains:
		- A numeric identification code
		- A set of attributes
		- Optional user-supplied data
- Three types of Event Logs:
	- System: system related apps and drivers
	- Application: user-level apps
	- Security
	- LOOK ON SLIDES

## UNIX Syslog
- UNIX general purpose logging system
- Elements:
	- syslog()
	- logger
	- /etc/syslog.conf
	- syslogd

## Syslog Services
- Basic service provides 
	- A means of capturing relevant events
	- A storage facility
	- A protocol for transmitting LOOK ON SLIDES

## Syslog Protocol
- Transport allowing host to send IP event notification messages to syslog servers
	- Provides a very general message format
	- LOOK ON SLIDES
- SysLog security measures
	- LOOK ON SLIDES
	- emerg
	- alert
	- LOOK ON SLIDES

## Logging at Applicaiton Level
- Privileged applications present security issues
	- May not be captured by system/user-level audit data

## Interposable Libraries
- LOOK ON SLIDES

# LOOK ON SLIDES

## Dynamic Binary Rewriting
- can be used with both statically and dynamically linked programs
- # LOOK ON SLIDES

## Audit Trial Analysis
- Analysis programs and procedures vary widley
- Must understand context of log entries
- LOOK ON SLIDES

## Types of Audit Trial Analysis
- Audit Trials can be used in multiple ways
	- This depends in part on when done
- Possibilities include
	- Audit trial review after an event

## Audit Review Capabilitity
- provides administrator with information LOOK ON SLIDES

## Approaches to Data Analaysis
- Basic Alerting
- Baselining
- Windowing
- Correlation
- LOOK ON SLIDES

# LOOK ON SLIDES

## SIEM Systems
- Software is centralized logging software package similar to syslog
- Two general configuration approaches:
	- Agentless
		- SIEM server recieves data from individual log generating hosts
	- Agent-based
		- Each machine has an SIEM for real-time analysis
- Able to recognize a lot of LOG formats
	- Normalizes entries
	- Deletes not needed / not relevent information
	- Combines data to determine patterns, prioritize events, and the like
- ## LOOK ON SLIDES, SAID TO REVIEW FOR EXAM THIS SLIDE