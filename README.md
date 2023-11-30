# Vulnerabilities

A vulnerability refers to a weakness in the design or implementation of a system that can be 
exploited to compromise the security of the system. It is frequently a security loophole that 
enables an attacker to enter the system by bypassing user authentication

# Common Reasons for the Existence of Vulnerabilities

## - Hardware or software misconfiguration

The insecure configuration of the hardware or software in a network can lead to
security loopholes. For example, a misconfiguration or the use of an unencrypted
protocol may lead to network intrusions, resulting in the leakage of sensitive
information. While a misconfiguration of hardware may allow attackers to obtain access
to the network or system, a misconfiguration of software may allow attackers to obtain
access to applications and data

## - Insecure or poor design of network and application

An improper and insecure design of a network may make it susceptible to various
threats and potential data loss. For example, if firewalls, IDS, and virtual private network
(VPN) technologies are not implemented securely, they can expose the network to
numerous threats

## - Inherent technology weaknesses

If the hardware or software is not capable of defending the network against certain
types of attacks, the network will be vulnerable to those attacks. Certain hardware,
applications, or web browsers tend to be prone to attacks such as DoS or man-in-themiddle attacks.
For example, systems running old versions of web browsers are prone to distributed attacks. If systems are not updated, a small Trojan attack can force the user 
to scan and clean the entire storage in the machine, which often leads to data loss.

## - End-user carelessness

End-user carelessness considerably impacts network security. Human behavior is fairly 
susceptible to various types of attacks and can be exploited to effect serious outcomes, 
including data loss and information leakage. Intruders can obtain sensitive information 
through various social engineering techniques. The sharing of account information or 
login credentials by users with potentially malicious entities can lead to the loss of data 
or exploitation of the information. Connecting systems to an insecure network can also 
lead to attacks from third parties

## - Intentional end-user acts

Ex-employees who continue to have access to shared drives can misuse them by 
revealing the company’s sensitive information. Such an act is called an intentional enduser act and can lead to heavy data and financial losses for the company


# Vulnerability Classification

## - Misconfiguration

Misconfiguration is the most common vulnerability and is mainly caused by human 
error, which allows attackers to gain unauthorized access to the system. It may happen 
intentionally or unintentionally and affects web servers, application platforms, 
databases, and networks

The following are some examples of misconfiguration:

An application running with debug enabled
- Unnecessary administrative ports that are open for an application 
- Running outdated software on the system
- Running unnecessary services on a machine
- Outbound connections to various Internet services
- Using misconfigured SSL certificates or default certificates
- Improperly authenticated external systems 
- Incorrect folder permissions
- Default accounts or passwords
- Set up or configuration pages enabled
- Disabling security settings and features

Attackers can easily detect these misconfigurations using scanning tools and then 
exploit the backend systems. Therefore, the administrators must change the default 
configuration of devices and optimize device security.

##  Default Installations

Default installations are usually user-friendly — especially when the device is being used
for the first time when the primary concern is the usability of the device rather than the
device’s security. In some cases, infected devices may not contain any valuable
information, but are connected to networks or systems that have confidential
information that would result in a data breach. Failing to change the default settings
while deploying the software or hardware allows the attacker to guess the settings to
break into the system.

##  Buffer Overflows

Buffer overflows are common software vulnerabilities that happen due to coding errors
that allow attackers to gain access to the target system. In a buffer overflow attack, the
attackers undermine the functioning of programs and try to take control of the system
by writing content beyond the allocated size of the buffer. Insufficient bounds checking
in the program is the root cause. The buffer is not able to handle data beyond its limit,
causing the flow of data to adjacent memory locations and overwriting their data
values. Systems often crash, become unstable, or show erratic program behavior when
buffer overflow occurs.

##  Unpatched Servers

Servers are an essential component of the infrastructure of any organization. There are
several cases where organizations run unpatched and misconfigured servers that
compromise the security and integrity of the data in their system. Hackers look out for
these vulnerabilities in the servers and exploit them. As these unpatched servers are a
hub for the attackers, they serve as an entry point into the network. This can lead to the
exposure of private data, financial loss, and discontinuation of operations. Updating
software regularly and maintaining systems properly by patching and fixing bugs can
help in mitigating the vulnerabilities caused by unpatched servers

##  Design Flaws

Vulnerabilities due to design flaws are universal to all operating devices and systems.
Design vulnerabilities such as incorrect encryption or the poor validation of data refer to
logical flaws in the functionality of the system that attackers exploit to bypass the
detection mechanism and acquire access to a secure system.

##  Operating System Flaws

Due to vulnerabilities in the operating systems, applications such as trojans, worms, and
viruses pose threats. These attacks use malicious code, script, or unwanted software,
which results in the loss of sensitive information and control of computer operations.
Timely patching of the OS, installing minimal software applications, and using
applications with firewall capabilities are essential steps that an administrator must take
to protect the OS from attacks.

##  Application Flaws

Application flaws are vulnerabilities in applications that are exploited by the attackers.
Applications should be secured using the validation and authorization of the user.
Flawed applications pose security threats such as data tampering and unauthorized
access to configuration stores. If the applications are not secured, sensitive information
may be lost or corrupted. Hence, developers must understand the anatomy of common
security vulnerabilities and develop highly secure applications by providing proper user
validation and authorization

##  Open Services

Open ports and services may lead to the loss of data or DoS attacks and allow attackers
to perform further attacks on other connected devices. Administrators must
continuously check for unnecessary or insecure ports and services to reduce the risk to
the network

##  Default Passwords

Manufacturers provide users with default passwords to access the device during its
initial set-up, which users must change for future use. When users forget to update the
passwords and continue using the default passwords, they make devices and systems
vulnerable to various attacks, such as brute force and dictionary attacks. Attackers
exploit this vulnerability to obtain access to the system. Passwords should be kept
confidential; failing to protect the confidentiality of a password allows the system to be
easily compromised.

##  Zero-Day Vulnerabilities

Zero-day vulnerabilities are unknown vulnerabilities in software/hardware that are
exposed but not yet patched. These are exploited by the attackers before being
acknowledged and patched by the software developers or security analysts. Zero-day
vulnerabilities are one of the major cyber threats that continuously expose vulnerable
systems until they get patched.

##  Legacy Platform Vulnerabilities

Legacy platform vulnerabilities are exposed from old or familiar codes. However, they
could cause costly data breaches for organizations. Using these outdated codes,
attackers can easily discover zero-day vulnerabilities in the system or software that are
not yet patched.


# Impact of Vulnerabilities

##  Information disclosure:
A website or application may expose system-specific 
information.

##  Denial of service:
Vulnerabilities may prevent users from accessing website services or 
other resources

##  Privilege escalation:
 Attackers may gain elevated access to a protected system or 
resources.

##  Unauthorized access:
 Attackers may gain unauthorized access to a system, a network, 
data, or an application.

##  Identity theft: 
Attackers may be able to steal the personal or financial information of 
users to commit fraud with their identity.

##  Data exfiltration:
Vulnerabilities may lead to the unauthorized retrieval and 
transmission of sensitive data

##  Reputational damage: 
Vulnerabilities may cause reputational damage to a company’s 
products and security. Reputational damage has a direct impact on customers, sales, 
and profit.

##  Financial loss: 
Reputational damage may lead to business loss. Further, vulnerability 
exploitation may lead to expenses for recovering damaged IT infrastructure.

##  Legal consequences:
If customers’ personal data are compromised, the organization 
may need to face legal consequences in the form of fines and regulatory sanctions

##  Hold footprints: 
Vulnerabilities may allow attackers to stay undetected even after 
executing an attack.

##  Remote code execution:
Vulnerabilities may allow the execution of arbitrary code from 
remote servers

##  Malware installation:
Vulnerabilities can make it easy to infect with and spread viruses 
in a network.

##  Data modification:
Vulnerabilities may allow attackers to intercept and alter data in 
transit.



