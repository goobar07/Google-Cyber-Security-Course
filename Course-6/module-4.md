# Sound the Alarm: Detection and Response

## Module 4 - Network traffic and logs using IDS and SIEM tools

### Learnings

- Read and analyze logs
- Interpret signatures
- Search in SIEM tools 


### Overview of logs

**Log**

A record of events that occur within an organization's systems

**Log details**

- Date
- Time
- Location
- Action
- Names

**Log analysis**

The process of examining logs to identify events of interest

**Log types**

- Network
- System
- Application
- Security
- Authentication

**Logs contain**

- Timestamps
- System characteristics
- Action

**Commonly used log formats**

- Syslog
- JavaScript Object Notation (JSON)
- eXtensible Markup Language (XML)
- Comma Separated Values (CSV)


### Overview of intrusion detection systems (IDS)

**Telemetry**

The collection and transmission of data for analysis

**Intrusion detection system (IDS)**

An application that monitors activity and alerts on possible intrusions

**Endpoint**

Any device connected on a network

**Host-based intrusion detection system**

An application that monitors the activity of the host on which it's installed

**Network-based intrusion detection system**

An application that collects and monitors network traffic and network data

**Signature analysis**

A detection method used to find events of interest

**Components of a NIDS rule**

1. Action
2. Header
3. Rule options

**Action**

- Detemines the action to take if the rule criteria is met
- Alert, pass, or reject

**Header**

- Source and destination IP addresses
- Source and destination ports
- Protocols
- Traffic direction

**Rule options**

- Depends on what are you looking for
- Usually seprated by semi-colons and enclosed in parantheses
- Contains message, signature id, and revision

**Suricata format types**

- EVE JSON - Extensible Event Format JavaScript Object Notation

**Suricata log types**

- Alert logs
- Network telemetry logs


### Overview of security information event management (SIEM) tools

**Security Information and Event Management (SIEM)**

An application that collects and analyzes log data to monitor critical activities in an organization

**Search Processing Language (SPL)**

Splunk's query language

**YARA-L (used in chronicle)**

A computer language used to create rules for searching through ingested log data

**Types of search (chronicle)**

1. UDM search
2. Raw log seach

