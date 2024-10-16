# Voice over Long Term Evolution (VoLTE) and the IMS

**Product ID**: 23006
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: VOLTE
**Vendor Code**: A3
**Vendor Name**: Alta3
**URL**: [Course Link](https://www.fastlaneus.com/course/alta3-volte)

## Objective
nan

## Essentials
It is recommended to take: (!) .

## Audience
nan

## Outline
1.	IMS Architecture & SIP Proxies 


- Standards Bodies 
- Understanding the 3GPP
- 3rd Generation Partnership Project
- The Network Operators Strike Back: ETSI TISPAN NGN, 3GPP2, & Cablelabs
- IETF & RFCs
- VoLTE Introduction 
- VoLTE + IMS Advantages
- Legacy vs. IMS
- Traditional User Database Management
- Why VoIP Central Control Can Not Compete with IMS
- The 3GPP IMS Architecture
- VoLTE and IMS Architecture Analysis
- The Building Blocks 
- The IMS Core (IP Multimedia Subsystem)
- IMS Core Components
- IBCF and TrGW
- The HSS (Home Subscriber Server)
- The SLF (Subscription Locator Function)
- The EPC (Evolved Packet Core)
- The E-UTRAN (Evolved UMTS Radio Access Network)
- The UTRAN (UMTS Terrestrial Radio Access Network)
- PCRF
- PCRF and its Interfaces
- Call Control Paths 
- The SERVICE PATH = The Half Call – AS Formed by the SIP REGISTRATION
- An IMS to IMS Call Analysis
- Call Control and Media Paths
- The IMS Half Call Concept
- Application Servers (AS)
- Serving Call Session Function (S-CSCF)
- Roaming and Visited 
- Visited Network vs. Home Network
- Proxy Call Session Function (P-CSCF)
- S5 (Local Breakout) and Registration
- S8 Access and Registration
- VoLTE Access 
- Intro to Bearers & APNs
- The Evolved Packet Core Component Analysis
- PDCP, RLC, MAC, PHY, and the LTE Grid
- Call Flow 
- Intra Domain Service Path Originating
- Intra Domain Service Path Terminating
- Intra Domain Call
- Intra Domain Routing
- Intra Domain Routing Decision
- Intra Domain Call End to End
- Inter-domain Call, Intra-domain Service Paths
- Inter-domain Call Routing
- Cross Domain Routing Decision
- IMS Border Control Function and Transition Gateway
- Inter-domain Roaming
- Inter-domain Call While Roaming
- Both UEs Roaming Plus Inter-Domain Call
- Both UEs Roaming Plus Inter-Domain Call Control Path
2.	IMS Identifiers 


- IMS IDs 
- IMS Identifiers
- UML Model of the Data Downloaded over Cx Interface
- UICC 
- UICC (Universal Integrated Circuit Card)
- IMS URI 
- IMSI – International Mobile Subscriber Identity  [im-zee]
- IMS Specific Numbering, Addressing and ID
- Home Network Domain Name
3.	VoLTE and IMS Architecture 


- HSS 
- The HSS (Home Subscriber Server)
- The SLF (Subscription Locator Function)
- CSCF (Call/Session Control Function)
- P-CSCF (Proxy-Call/Session Control Function)
- I-CSCF (Interrogating-Call/Session Control Function)
- S-CSCF (Serving-Call/Session Control Function	)
- Breakout Gateway Control Function (BGCF)
- AS (Application Server)
- MRF - MRFC / MRFP (Media Resource Function Controller / Processor)
- Policy and Charging Rules Function and the EPC
- Mobility Management Entity (MME)
- Serving Gateway (S-GW)
- PDN Gateway (P-GW)
4.	Bearer and APNs 


- Commonly Utilized Bearers 
- Bearer Components from the E-UTRAN through the EPC
- VoLTE Bearers from the E-UTRAN through the EPC
- Internet Bearers from E-UTRAN through the EPC
5.	Power up Process 


- Overview 
- Frequency Scanning and UE Categories
- System Acquisition and RRC Connection Setup 
- Primary Synchronization Signal (PSS)
- Cell-ID & Secondary Synchronization Signal (SSS)
- Physical Broadcast Channel (PBCH)
- Master Information Block (MIB)
- Transport Downlink Shared Channel (DL-SCH) for SIB1
- System Information Block type 1 (SIB1)
- Downlink Shared Channel (DL-SCH) & SIB2
- Uplink Synchronization
- RRC CONNECTED and RRC IDLE
- SIB1 – SIB12
- Cell Selection
- Network Attach 
- The IMS APN Bearer Establishment
- Attach Request, NAS, Authentication Process
- Encryption and ESM Info
- Location Request and Response
- Create Session Request and Response
- CCR AAA Request and Response
- Create Session Response SGW to MME to eNB
- Initial Context Setup and RRC Reconfiguration
- UE Capability and ICR
- Modify Bearer and EMM Info
- Modify Bearer Response, AAA Responses and the SIP REGISTER
- The Spreading Sequence
- How does a UE request bandwidth in order to gain access to request bandwidth?
6.	Handover Between eNodeBs 


- Idle Mode 
- Cell Reselection
- Discontinuous Reception (DRX) with Long and Short DRX
- How DRX Timers Apply the LTE Grid
- Idle Mode Within and Beyond the UE
- Active UE 
- Intra-frequency Mobility (3GPP TS 23.401)
- Intra MME SGW Handover Using the X2 Interface
- S1-based Handover with S-GW & MME Relocation

7.	Tracking and Paging A UE 


- Overview 
- Tracking Area Defined
- Tracking Area Identifiers
- Tracking Area Lists
- Relationship of MME Pool Areas, TA, and S-GW Service Areas
- Tracking and Paging a UE 
- Tracking Area Update (TAU)
- Idle Mode
- UE Entering Idle Mode
- Paging an Idle UE
8.	SIP Architecture 

	
- The Big Picture 
- Key VoLTE and IMS Protocols
- SIP Message Format 
- SIP User Agent (UA)
- SIP Request and Response Format
- IMS SIP Transactions 
- SIP Requests (Methods)
- SIP Response Codes
- A SIP Transaction Defined
- PRACK and The 100rel Process (RFC 3262)
- VoLTE to VoLTE SIP Transactions
- SIP Control Path 
- Trust Chain
- SIP Architecture
- B2BUA Example: TAS
- Mapping SIP dialogs through an Application Server
- Proxy vs. B2BUA 
- User Identities: Address-of-Records and Contact-URIs
- SIP URI 
- SIP and SIPS URI Structure Components (RFC 3261)
9.	SIP Via Paths 


- The Via Header 
- The “Via:” Path: How A Response Finds Its Way Back
- The SIP Transaction 
- Via: Lifetime = per Transaction! (Not the Entire Duration of the Dialog)
- Impact of Via Path on the SIP Dialog 
- What Path Does the ACK Take?
10. SIP Route Headers 


- RR and Route 
- The Record-Route and Route Function
- Looping 
- Loop Detection
11. Basic SIP & IMS Specific Headers 


- Start Line
- Via:
- Via: branch parameter
- From:
- To:
- Call-ID:
- SIP Dialog ID
- Contact:
- CSeq: (Command Sequence)
- Content-Type: 
- Content-Type: message/sipfrag RFC 3420
- Content-Length:
- Max-Forwards:
- Allow:
- OPTIONS
- User-Agent:
- Supported:
- P-Preferred-Identity: and Privacy: RFC 3325 (UA to P-CSCF)
- P-Preferred-Identity: to P-Asserted-Identity:
- P-Access-Network-Info: RFC 3455
- Authorization: RFC 3261 Section 22.2
- Path:  RFC 3327
- Service-Route: RFC 3608
- Introduction to SigComp 
- SigComp Example
12. Diameter 


- Overview 
- RADIUS vs DIAMETER
- Diameter Protocol
- Diameter Message Structure 
- The AVP Chain: Type – Length - Value
- AVPs Encapsulated Inside an AVP
- Diameter Header Structure
- AVP Structure
- Diameter Message Example
- Diameter Message as  Wireshark Would Display it
- Customization 
- Diameter Code Customization
- IMS’s Diameter Cx Command Codes Values
- Diameter AVPs Defined for the Cx Interface
- Diameter AVPs: Rx Interface Codes
- Registration Call Flow 
- Challenge
- Authorization
- Registration Status
- Registration Termination Request
- Registration Status at the P-CSCF
- SCTP 
- Traditional Transport Layers (OSI Layer 4)
- Stream Control Transmission Protocol (RFC 4960)
- SCTP High Durability Connections
- Setting Up An Association
- The SCTP Protocol Data Unit
- Head-of-Line-Blocking Avoidance
- Chunking & Bundling
13. H.248 


- Overview 
- H.248 Call Flow Example
- H.248 Common Controller
- H.248 Call Control Model
- H.248 in the IMS Core 
- H.248 Call Control Model
14. Initial Filter Criteria (iFC) 


- iFC Function 
- iFC Logic
- Data Structure 
- UML Model of the Data Downloaded Over Cx Interface
- iFC Logic 
- Disjunctive Normal Form
- Conjunctive Normal Form
- iFC Example 
- Setting Up A TAS for Feature Enablement – (Using three.ims Domain)
- Service Profile
15. Presence 


- The Presence Model 
- Presentity and Watcher
- PUBLISH
- SUBSCRIBE
- NOTIFY
- IMS Call Flow 
- Cross Domain SUBSCRIBE Example
- PUBLISH presentity and Cross Domain NOTIFY to Watchers
- Basic vs. Rich Presence 
- Presence Information Data Format (PIDF)  RFC 3863
- Rich Presence Information Data format (RPID)  RFC 4480
- Message Examples 
- PUBLISH (Initial)
- SUBSCRIBE (Watcher)
- NOTIFY (Initial Status)
- PUBLISH (Updated status)
- NOTIFY  (Updated status)
16. Session Description Protocol (SDP) 


- Overview 
- SDP Establishes ½ the Media Channel
- SDP: RFC 4566
- RTP is “simplex”
- a=sendonly means what?
- Media Direction’s Impact on RTCP
- Lines 
- Version, v=
- Origin, o=
- Session, s=
- Connection, c=
- Time, t=
- Media Description, m=
- Bandwidth, b=
- The “a=” Attribute Header (Extends SDP)
- Attribute, a=fmtp, Format Specific Parameters
- Mode
- Packet Interval
- Offer/Answer 
- Overview of Offer/Answer
- OFFER/ANSWER Examples
- SDP Offer/Answer Model
- UPDATE RFC 3311
- Preconditions 
- Preconditions; a=curr and a=des
- Preconditions Call Flow
- Preconditions E2E and Segmented


17. QoS 
- Enforcing QoS 
- Linking the IMS Core to the EPC
- PCRF Interfaces: Sp Ud, Np, Rx, Sy, Gy, Gyn, Gzn, Gz, Sd, Gx, Gxx
- 3GPP Policy Architecture (Simplified)
- Roaming scenarios: H-PCRF and V-PCRF
- PGW Gate/Pinhole Defined
- Converting SDP to a Gate
- VoIP Service Requirements and the QoS Solution
- Default Bearer, Dedicated Bearer, QCI, ARP, GBR
- Rx and Gx Messages
- IMS Dedicated Bearer Setup
- LTE Dedicated Bearer Setup AAR, CCR, Create Bearer Req


18. IMS Call Flow Examples 
- SIP REGISTER 
- Initial IMS REGISTRATION
- IMS SIP Registration and the DIAMETER Query
- IMS SIP Registration and DIAMETER Response
- IMS SIP Registration REGISTRATION to SCSCF
- IMS SIP Registration aka MD5 CHALLENGE (401)
- IMS SIP Registration Challenge Response
- IMS SIP Registration Confirmed; 200
- IMS SIP Registration; SERVICE PATH Determination
- De-Registration 
- UE Initiated De-Registration
- Network Initiated De-Registration
- Media Relay 
- IMS Call Setup with Media Relay
- Terminal Initiated Session Release


19. Circuit Switched Fallback 
- CSFB Originating 
- 3G and 4G Update Message Review: LAU, TAU, RAU
- Combined EPS/IMSI Message
- How SR-VCC Interoperates with the Combined Attach
- Extended Service Request
- Connection Management Service Request
- CSFB Terminating 
- The IAM and Paging
- Service Request and Context Mod with CSFB
- CCO and Context Release
- Suspend an Update Bearers
- Paging Response
- Active Call
- Ladder Diagram 
- CSFB Ladder Diagram End to End


20. SR-VCC 
- Overview 
- Comparing VCC, ICS, and IMS-SC
- Apply VCC, ICS, and IMS-SC technology to CSFB and SR-VCC
- Routing Number 
- Mobile Station International Subscriber Directory Number (MSISDN)
- Routing Number
- Which number “Wins” when Routing?
- Which number does the server need?
- STN-SR, IMRN, and gsmSCF Routing Numbers
- How MSISDN and STN are included in SIP messages
- SR-VCC Control Paths 
- Services that must be optimized for SRVCC
- The Media Path 
- Direct Media
- The Role of the ATCF/ATGW and Media Anchoring
- Interoperation between ATCF/ATGW and MSC (4G to 3G Media)
- SR-VCC example: UTRAN to UTRAN Call Control and Media Paths
- Interfacing SR-VCC with a MSC not optimized for SRVCC
- SR-VCC Call Flow 
- SR-VCC PS to CS Transfer Message by Message
- SRVCC PS to CS Transfer
- Control and Media Paths Following SR-VCC-controlled PS to CS Transfer
- SRVCC from E-UTRAN to GERAN without DTM Support


21. Emergency Call Flow 
- References 
- 3GPP Emergency
- Components 
- IMS Emergency Sessions Topology and Message Flow
- IP Multimedia Subsystem (IMS) Emergency Sessions Call Flow


22. Charging in the IMS 
- Charging Systems Overview 
- Charging in the IMS
- IMS Charging Mechanisms
- Charging Interworking Functions & Reference Points
- Offline Charging Functions
- Online Charging Functions
- Online (Ro) and Offline (Rf) Charging Commands
- Charging and Call Flow 
- P-Charging-Vector:  RFC 3455
- P-Charging-Function-Addresses
- IMS Call Setup


23. DNS 
- Zone File 
- DNS root zone has 13 named authorities
- How a Zone file appears in Linux – Bind9
- How $ORIGIN Impacts the Zone File
- Sample Zone File Organized into a Table (strictly for teaching)
- “SOA” Record – The Start of Authority
- Locating SIP Servers 
- NS-record
- A-record
- SRV-record
- NAPTR – Naming Authority Pointer
- RFC 3263 – Locating SIP Servers - NAPTR
- RFC 3263 – Locating SIP Servers - SRV
- RFC 3263 – Locating SIP Servers - A-record
- RFC 3263 – Locating SIP Servers – INVITE


LABS: Wireshark Traces, Call Flows & Examples 
- Lab 0.	Understanding the Lab Environment
- Lab 1.	Using Wireshark
- Lab 2.	SIP User Agent Configuration
- Lab 3.	Direct UA to UA Routing with No Proxy
- Lab 4.	Proxy Based SIP Routing
- Lab 5.	Adding Authorized UAs to a Domain
- Lab 6.	Registering a SIP UA (Capturing a SIP REGISTER with Wireshark)
- Lab 7.	Intra Domain Routing (SIP routing within the same domain)
- Lab 8.	Inter Domain Routing (SIP routing to different domains)
- Lab 9.	Digit translation
- Lab 10.	Prefix domain transfer (PDT) management
- Lab 11.	Capturing a “normal’ SIP call via Wireshark
- Lab 12.	Capturing a call to a vacant seat via Wireshark
- Lab 13.	Capturing a call to a busy seat via Wireshark
- Lab 14.	Capturing a call-forward (3xx response) via Wireshark
- Lab 15.	Via, Route, and Record-Route headers
- Lab 16.	Examining and manipulating Max-Forwards header
- Lab 17.	Capturing SDP offer and answer
- Lab 18.	Silence suppression
- Lab 19.	DTMF RFC 2833 and SIP INFO
- Lab 20.	SIP Back-to-Back UA configuration example (Asterisk)
- Lab 21.	REGISTER SIP device to Back-to-Back UA
- Lab 22.	Capture SIP call through a Back-to-Back UA and compare to a Proxy
- Lab 23.	RTP Relay
- Lab 24.	Real-Time Control Protocol (RTCP)
- Lab 25.	Routing with DNS / ENUM
- Lab 26.	Testing Connectivity using SIP OPTIONS
- Lab 27.	SIP testing with SIP-p
- Lab 28: 	IMS Service Profile
- Lab 29: 	Roaming
- Lab 30: 	Exploring the Home S-CSCF Set
- Lab 31: 	Registration Termination Request (RTR)
- Lab 32: 	Push Profile Request

## Summary
Learn VoLTE, IMS, and the SIP protocol in this intensive 5-day class. This class thoroughly studies call flow through the EU-TRAN, the EPC and into the IMS core. We will make the entire picture clear and backup all that we teach with call flows and live labs using an IMS platform. 

This course also covers enough of other technologies like Diameter and DNS to allow you to understand the complete picture. The lessons in this course are clear, very technical, and always practical, and since much of it is hands-on, you can investigate and reinforce each lesson.

## Course Duration
5 days

## Last Changed
2024-08-22T19:32:09.000Z
