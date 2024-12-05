<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->
<div id="top-of-doc"></div>

# cyber-notes %Y |

[My Github](https://github.com/popados) | [Jump to End](#end-of-doc)

---

## CyberTrack -> | Started 7/28/2024

> Welcome to the Cyber4RAM badge, a badge designed to build awareness about cybersecurity among those who currently work or plan to work in the areas of robotics/automation/mechatronics. Since so many advanced manufacturing technologies are now connected, it is critical that technicians understand some cybersecurity basics in order to keep the machines they operate protected from outside threats.
> The Cyber4RAM badge is designed to expose learners' to content that will take the basic principles of cybersecurity and apply them to robotics/automation/mechatronics and other Industry 4.0 technologies. As our manufacturing environments integrate more
> technology into their operation, operational technicians must be aware of the many cybersecurity threats that exist in an Internet of Things (IoT) environment that now exists on manufacturing floors.

Protect machines and software connected to IoT and other manufacturing tech.
To protect and maintain the existance of:

- Robotics
- Automation
- Mechatronics(???)

---

### Day 001 | 7/28/2024 - Sunday

#### **Risk Analysis**

- High Risk
  - Catastrophic possibilities.
  - Negligence
    - no actions or controls taken to a lower risk level
- Lower Risk
  - Due care
  - Risk exists
  - Steps in place to minimize risk
- Acceptable Risk

  - Lots of control implemented to prevent risk
  - Due diligence

    - Cannot fully eliminate risk - Can minimize further
      **Risk Management**

  -

  - Assets

    - Intanglible
    - Tanglible

  - Threats

    - Intentional
      - Phishing etc
    - Unintentional
      - Accidental hacking/keylogger/malfunction
    - Unexpected Event
      - Natural disasters

  - Threat Agent
    - group or individual that exploit a system
      - vulnerabilities
      - other damages
  - Vulnerability
    - Flaw
    - Weakness
    - Cause harm
  - Risk
    - probability of loss due to a threat
  - Countermeasure
    - Action
    - device
    - procedure
    - technique
    - reduces threat
  - Security Control
    - technical
    - physical
    - administrative policies
    - implement functions
      - avoid
      - offset
      - detect
      - minimize
    - preventative
    - detective
    - deterrent
    - compensating
    - recovery
    - corrective
  - Impact
    - The direct exposure to a vulnerability
    - damages
  - Exposure
    - The percentage of damage to the assets
  - Risk Assessment

    - ID of vulnerabilities and threats and assessing possible impacts

  - Identify Threats
    - Adware/Spyware
    - Service Disruption
    - Equipment Failure
    - Ransomware
    - Unauthorized Access
    - Malware
    - rogue security software
    - DDoS
    - Man in the Middle
    - Logic Bomb
    - Virus
    - RootKit
    - Password Cracking
    - Identity Theft
    - Worms

  **ITAM** and **ITSM**

  ITAM - > IT Asset Management

  ITSM - > IT Service Management

### Day 002 | 7/29/2024 - Monday

#### **Computer Languages**

```
- Define computer language
- List the characteristics of Python
- Explain the Python applications used in industry
- Understand the different types of software based computer viruses
```

- What is a computer language?

  - instructions for pc
  - communicate
  - multiple
  - compilers
  - machine or programming code

- Python

  - OOP
  - good language to learn
  - 1000 built in modules or functions
  - python is used with PLCs and IoT and Automation
  - _Artificial Intelligence (AI) and Machine Learning (ML)_
    - Python is helping to advance the science of emulating humans
  - _Cybersecurity_
    - Python can perform a multitude of security tasks, protecting critical systems and information from digital attacks
  - _Automation_
    - Python will continue to automate tasks traditionally performed by humans
  - _Data science_
    - Python has hundreds of libraries and frameworks that are growing the use of Python for data science
  - _Blockchain development_
    - Python can be used to create a digital public ledger that records online transactions, keeping them secur

- Macros
  - mini programs
  - series of instructions as a single command
  - store programming instructions for smaller IoT and may not run full featured

#### **Malware**

- Malicious software installed in many ways

_Types of Malware_

- **Viruses**
  - attached to a piece of executeable code of hosted app
    - executes on hosted app
    - search and destroy/deliver
      - payload can damage/reboot/delete
- **Worms**
  - attack the network and computer systems.
  - It doesn’t need assistance to self-replicate or
  - travel through a network
- **Trojans**
  - deceptive
  - disguised
    - games
    - apps
    - utilities
  - looks authorized
  - installled by user
    - often overlooked
- **Remote Access Trojan(RATs)**
  - allow bad actor to control pc from remote location
  - usually attached to phishing emails
  - free to access after compromised
- **Logic Bombs**
  - remains dormant until an event causes it to release its payload
  - authorized user installed
- **Keylogger**
  - attempt to capture and store users keystrokes
  - taken into a file for later access
- **Spyware**
  - Monitors or spies on activity
    - keystrokes
    - info
    - recordings
    - audio
    - etc
- **Adware**
  - unwanted ads
- **Bots / Botnets**
  - execute auto
  - allow remote attacker to take over system
  - interconnected computers or devices
  - multiple malicious bots
- **Rootkits**
  - A Rootkit is a collection of software programs that provide administrative access to a user’s system while hiding its presence on the user’s system.
- **Advanced Persistent Threats (APTs)**
  - remain on pc for awhile
  - require sophicated hacking/time/effort
  - grouped efforts
  - nation states or corps
  - backdoors
    - DNC email hack
  - attack pattern
    - develop a strat -> what you do
    - gain entry
    - maintain ongoing presence and write backdoors or new code
    - explore network and gain admin priv
    - stage attack to accomplish goal and maintain ongoing presence
- **Zero Day Attacks**
  - unknown flaw or software that leaves a syste vulnerable

### Day 003 | 8/03/2024 - Saturday

> Bob realizes that a program or user interface should always respond in the way that is least likely to astonish the user. When Microsoft removed the Start button from its operating system, Microsoft released an updated version adding the Start button back.

#### **Cybersecurity Principles:**

**Authoirzation Priciples**

- _Seperation_

  - Users in one domain cannot interaction with parent domains.

    - Child domains can be interacted with by parent users.
    - multiple privilege attributes are required to access a restricted resource

      > Data and/or systems are separated into logically-defined domains, and communication between domains must be authorized.

- _Complete Meditation_

  - Check all access with control

- _Least Privilege_

  - Everyone user and process can operate and the least set of privileges available to the role.

- _Fail Safe Defaults/Fail Secure_

  - Permission based

  - Will show full error messages not just what part is wrong.

> Bob will make access decisions based on permission rather than exclusion. If a hacker enters the wrong information, the system should reject the attempt with a message stating that the login failed and not state that just the password was incorrect.

- **Minimization Principles**

- Isolation

  - Public access away from critical resources(data, processes, etc)

  - prevent disclosure or tampering

    > Operating systems use various hardware and software technologies to enforce process isolation. For example, the processes and files of individual users should be isolated from one another except where it is explicitly desired.

- Encapsulation

  > Bob can use a specific form of isolation based on object-oriented functionality. Encapsulation hides the values or state of a structured data object inside a class (a domain of its own), preventing any direct access by unauthorized parties.

- **Trust Relationships**

  - trust boundry

    - authenticating other endpoint to stop masquerading
    - ensure the security of the communication to maintain the confidentiality of the data
    - prevention of data tampering

  - minimize trust surface
    > Trust must be created, not assumed. There should be clear distinctions between privilege levels when Bob accesses resources. If Bob logs in and is authenticated, he must also have authorization to access a resource.

- **Open Design**

  > Bob knows that the design of a security mechanism should be open and not depend on the secrecy of the design details or implementation.

  - RSA Encryption
    - large numbers ez to multiply hard to factor
    - factoring of large prime numbers is not easy

- **Usability**

- **Good Design Principles**

  - Modularity

    - Single purpose
    - independantly created
    - used in several systems - Understandable
    - Security is seperate and protected

  - Simplicity of Design
    - Economy of Mechanism
      - must be small and simple
  - Layering
    > Bob will use multiple, overlapping protection approaches to address the people, technology, and operational aspects of information systems. Defense in depth protects with a series of security mechanisms so that if one fails, others will be in place.
    - OSI Layers
    - Data
    - App
    - Host
    - Network
    - Perimeter
    - Physical
    - Procedures, Policies, and Awareness

**main tenets of information:**

- security—confidentiality,
- integrity
- availability of the system,
- sub-system
- system data.

---

### Day 004 | 8/14/2024 - Wednesday

#### **Privacy vs Security**

> Human error is the biggest issue with security and privacy

- **Privacy**

- **Security**
  - focused on ensuring CIA triad
    - Confidentiality
    - Integrity
    - Accessibility
  - (AAA) to help ensure that only authorized users can access data
    - _Authentication_
      - passwords
      - smart cards
      - biometrics
      - digital certificates
    - _Authorization_
      - physical access controls
      - network traffic filters
    - _Accounting_
      - Logs

#### **CIA Triad**

> The CIA Triad is a fundamental cybersecurity model that acts as a foundation in the development of security policies designed to protect data.

> In theory, the CIA Triad combines three distinct means of interacting with data to create a model for data security.

> The Triad is essential because it is a reliable and balanced way to assess data security. It weighs the relationship between confidentiality, integrity, and availability from an overarching perspective. The framework requires that any attempt to secure digital information will not weaken another pillar of defense.

---

#### **Tenets**

**Confidentiality**

- only authorized users have access
- protecting information
- who sees the document

**Intergity**

- trustworthiness and veracity of the data
- reliability and authentic
- any attempts to alter are logged and detectable

**Availability**

- when and where users need the info
- crucial
- data is only usable when accessed

<details>

<summary> The Cube </summary>

![Three-Sides to Cube](image-1.png)

![The Cube](./image.png)

</details>

### Day 004 | 9/9/2024 - Monday

**Digital Forensics**

- Define
- security
- list

use of tech to search for evidence

damage that occurred during a cyber event

any piece of tech that has:

- processor
- memory
- storage
- volatile
- RAM
- swap andd paging files
- disk
- logs
- arvhieved data
- capture a system image as early as possible
- conduct an analysis
- copyv fv
- original evidence not modded

> Volatile data must be collected first, as volatile data may change quickly. Examples of volatile data include RAM, swap and paging files, files on disk, logs, and archived data. It is important to capture a system image as early as possible, and then conduct an analysis on the copy of the image, ensuring that the original evidence is not modified. Additionally, network traffic and logs, video, other media need to be captured, along with timestamps.

Chain of custody
evidence gathered and documented

handleded and what is done with it

was protected from alteration

everyone who had contact with evidence

CHAIN OF DUSTODY MUST be clearly documented in all cases

---

### Day 005 | 8/15/2024 - Thursday

- The result of the incident is theft or misuse of confidential information of any type
- The incident affects the network infrastructure and services
- The incident provides unauthorized access to any resource on the network
- The incident provides a platform for launching attacks against a third party

collecting and preserving data
network forensics is analysis network traffic
mobile is from smart phone and tablets

---

## End of Document

---

[Jump to Top](#top-of-doc)

<div id="end-of-doc"></div>

<details>
<summary>Notes:</summary>
</details>
