# Cybersecurity Entry level Interview Questions #

### What is CIA triad?
The three letters in "CIA triad" stand for Confidentiality, Integrity, and Availability. The CIA triad is a common model that forms the basis for the development of security systems. They are used for finding vulnerabilities and methods for creating solutions. (Fortinet)

Confidentiality: Confidentiality involves the efforts of an organization to make sure data is kept secret or private. A key component of maintaining confidentiality is making sure that people without proper authorization are prevented from accessing assets important to your business.

Integrity: Integrity involves making sure your data is trustworthy and free from tampering. The integrity of your data is maintained only if the data is authentic, accurate, and reliable.

Availability: Systems, networks, and applications must be functioning as they should and when they should. Also, individuals with access to specific information must be able to consume it when they need to, and getting to the data should not take an inordinate amount of time.

### What is phishing?  ###

Phishing is a type of cyber attack where attackers pose as legitimate entities to trick users into providing sensitive information, such as passwords, credit card numbers. Phishing attacks are usually carried out via email, instant messaging...Etc.

### What is a firewall?

A firewall is a network security device that monitors and controls incoming and outgoing traffic based on predetermined security rules. It acts as a barrier between a trusted internal network and untrusted external networks. Basically it preventing unauthorized access and protecting the system from cyber threats.


### What do you mean by Network Sniffing?
Network sniffing is the process of monitoring and capturing data packets that pass through a network. Attackers use network sniffers to intercept sensitive information, like login credentials or private conversations.


### What is cipher text?
Cipher text is encrypted data that appears as random characters and is unreadable without the correct decryption key. When information is encrypted, it is converted from plain text to cipher text.

### What is encryption?

Encryption is the process of converting plain text into cipher text using an algorithm and encryption key. The purpose of encryption is to protect the confidentiality of data.

### What is decryption?
Decryption is the process of converting encrypted cipher text back into its original plain text form. Decryption requires the use of a decryption key. This process ensures that sensitive information is accessible only to authorized users.

### What is cryptography?
Cryptography is the practice of securing communication. Cryptography includes encryption, decryption, and digital signatures, ensuring confidentiality, integrity, and authenticity [CIA] of data.


### What is multi-factor authentication?
Multi-factor authentication is a mechanism in which it requires users to provide more than one form of authentication factor, such as something they know, something they have, and something they are. Ex:  username/password + OTP   and username/password + Fingerprint biometric

 
### Explain Vulnerability, Risk and Threat ? 

Vulnerability: Weakness in an information system, system security procedures, internal controls, or implementation that could be exploited or triggered by a threat source. (src: NIST)

Risk: The level of impact on agency operations (including mission functions, image, or reputation), agency assets, or individuals resulting from the operation of an information system given the potential impact of a threat and the likelihood of that threat occurring. (src: NIST)

Threat: Any circumstance or event with the potential to adversely impact organizational operations, organizational assets, individuals, other organizations, or the Nation through a system via unauthorized access, destruction, disclosure, modification of information, and/or denial of service. (src: NIST)

### What are HIDS and NIDS?
HIDS: HIDS means Host Intrusion Detection System. HIDS is located on each host.

NIDS: NIDS means Network Intrusion Detection System. NIDS is located in the network.

### What is SIEM?
Security Information and Event Management (SIEM), is a security solution that provides the real time logging of events in an environment. The actual purpose for event logging is to detect security threats.
In general, SIEM products have a number of features. The ones that interest us most as SOC analysts are: they filter the data that they collect and create alerts for any suspicious events. 

### What is TCP/IP Model? Explain the difference between OSI and TCP/IP model.
The TCP/IP model is the default method of data communication on the Internet. It was developed by the United States Department of Defense to enable the accurate and correct transmission of data between devices.

TCP/IP divides communication tasks into layers that keep the process standardized, without hardware and software providers doing the management themselves. The data packets must pass through four layers before they are received by the destination device, then TCP/IP goes through the layers in reverse order to put the message back into its original format. (Fortinet)

![image](https://github.com/user-attachments/assets/3a3b4cfe-8da5-45e0-a31f-4d4c5466399e)

### What is DHCP?
The Dynamic Host Configuration Protocol (DHCP) is a network management protocol used on Internet Protocol (IP) networks for automatically assigning IP addresses and other communication parameters to devices connected to the network using a client–server architecture.

### What is Salted Hashes
A salt is added to the hashing process to force their uniqueness, increase their complexity without increasing user requirements, and to mitigate password attacks like hash tables.

### What is Port Scanning?
Port scanning is a method of determining which ports on a network are open and could be receiving or sending data. It is also a process for sending packets to specific ports on a host and analyzing responses to identify vulnerabilities.

### What is Cyber Kill Chain?
Developed by Lockheed Martin, the Cyber Kill Chain® framework is part of the Intelligence Driven Defense® model for identification and prevention of cyber intrusions activity. The model identifies what the adversaries must complete in order to achieve their objective.

The seven steps of the Cyber Kill Chain® enhance visibility into an attack and enrich an analyst’s understanding of an adversary’s tactics, techniques and procedures. (Lockheed Martin)

![image](https://github.com/user-attachments/assets/afd9b56c-b26c-449c-9494-591890479394)


### What is Zero Trust security ?
The Zero Trust security model is a cybersecurity framework that operates on the principle of "never trust, always verify." It assumes that threats can come from both outside and inside the network and thus requires strict identity verification for every person and device trying to access resources on the network, regardless of whether they are within or outside the network perimeter.

### What is SQL Injection?
SQL Injections are critical attack methods where a web application directly includes unsanitized data provided by the user in SQL queries. (LetsDefend)

### Explain SQL Injection Types
There are 3 types of SQL Injections. These are:

In-Band SQLi (Classical SQLi): If a SQL query is sent and a replied to over the same channel, we call these In-band SQLi. It is easier for attackers to exploit these compared to other SQLi categories.

Inferential SQLi (Blind SQLi): SQL queries that receive a reply that cannot be seen are called Inferential SQLi. They are called Blind SQLi because the reply cannot be seen.

Out-of-Band SQLi: If the reply to a SQL query is communicated over a different channel then this type of SQLi is called Out-of-Band SQLi. For example, if the attacker is receiving replies to his SQL queries over the DNS this is called an Out-of-Band SQLi.

### What is a three-way handshake ? 

The three-way handshake is a three-step process used in TCP/IP networking to establish a reliable connection between a client and a server before data transmission 
# Step 1: SYN (Synchronization) from Client to Server 
The client sends a SYN (synchronization) packet to the server, initiating the connection request. 
This packet includes the client's initial sequence number. 
# Step 2: SYN-ACK (Synchronization-Acknowledgement) from Server to Client 
The server, upon receiving the SYN packet, responds with a SYN-ACK packet. 
This packet acknowledges the client's SYN and includes the server's initial sequence number and the expected sequence number from the client (which is the client's SYN number + 1). 
# Step 3: ACK (Acknowledgement) from Client to Server 
The client, upon receiving the SYN-ACK, sends an ACK packet back to the server. 

### What is DNS?
DNS stands for Domain Name System, which is a system that translates domain names into IP addresses

### Explain how JWT works ?
JWT (short for JSON Web Token and pronounced “jot”) is an open standard used to create compact, self-contained tokens used for securely transmitting information between different applications or services.
The three main components of a JWT are the:

Header
Payload
Signature
Refer# https://www.descope.com/learn/post/jwt 

### Differentiate between TCP &amp; UDP?
TCP (Transmission Control Protocol) is a connection-oriented, reliable protocol prioritizing data integrity and order, while UDP (User Datagram Protocol) is a connectionless, faster protocol prioritizing speed and efficiency, sacrificing reliability

### What is risk management ?
Risk management is the systematic process of identifying, assessing, and mitigating threats or uncertainties that can affect your organization.

### What’s the difference between encoding, encryption, and hashing?
Encoding converts data for representation or transmission, encryption secures data by making it unreadable without a key, and hashing generates a unique, fixed-length "fingerprint" of data for integrity checks, with hashing being a one-way process. 

### Can you describe rainbow tables? 
A rainbow table is a password hacking tool that uses a precomputed table of reversed password hashes to crack passwords in a database.

