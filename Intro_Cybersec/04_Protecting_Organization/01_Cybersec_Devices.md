Security Appliances
Security appliances can be standalone devices like a router or software tools that are run on a network device. They fall into six general categories.
    - Routers: While routers are primarily used to interconnect various network segments together, they usually also provide basic traffic filtering capabilities. This information can help you define which computers from a given network segment can communicate with which network segments.
    - Firewalls: Firewalls can look deeper into the network traffic itself and identify malicious behavior that has to be blocked. Firewalls can have sophisticated security policies applied to the traffic that is passing through them.
    - Intrusion Prevention Systems: IPS systems use a set of traffic signatures that match and block malicious traffic and attacks.
    - Virtual Private Networks: VPN systems let remote employees use a secure encrypted tunnel from their mobile computer and securely connect back to the organization’s network. VPN systems can also securely interconnect branch offices with the central office network.
    - Antimalware: These systems use signatures or behavioral analysis of applications to identify and block malicious code from being executed.
    - Other: Other security devices include web and email security appliances, decryption devices, client access control servers and security management systems.

    Cisco Integrated Services Router (ISR) 4000. These routers have many capabilities, including traffic filtering, the ability to run an intrusion prevention system (IPS), encryption and VPN capabilities for secure encrypted tunneling.
    
    Cisco’s Firepower 4100 Series is a next generation firewall that has all the capabilities of an ISR router, as well as advanced network management and analytics. It can help you to see what’s happening on the network so that you can detect attacks earlier.
    
    Cisco’s AnyConnect Secure Mobility Client is a VPN system that lets remote workers use a secure encrypted tunnel from their mobile computer to securely connect back to the organization’s network. All Cisco security appliances are equipped with a VPN server and client technology, designed for secure encrypted tunneling.
    
    Cisco’s Advanced Malware Protection (AMP) is installed in next generation Cisco routers, firewalls, IPS devices and web and email security appliances. It can also be installed as software in host computers.


Firewalls
In computer networking, a firewall is designed to control or filter which communications are allowed in and which are allowed out of a device or network. A firewall can be installed on a single computer with the purpose of protecting that one computer (host-based firewall) or it can be a standalone network device that protects an entire network of computers and all of the host devices on that network (network-based firewall).
As computer and network attacks have become more sophisticated, new types of firewalls have been developed, which serve different purposes.

Network layer firewall
This filters communications based on source and destination IP addresses.
Transport layer firewall
Filters communications based on source and destination data ports, as well as connection states.
Application layer firewall
Filters communications based on an application, program or service.
Context aware layer firewall
Filters communications based on the user, device, role, application type and threat profile.
Proxy server
Filters web content requests like URLs, domain names and media types.
Reverse proxy server
Placed in front of web servers, reverse proxy servers protect, hide, offload and distribute to web servers.
Networks address translation (NAT) firewall
This firewall hides or masquerades the private addresses of network hosts.
Host-based firewall
Filters ports and system services calls on a single computer operating system.

Port scanning
In networking, each application running on a device is assigned an identifier called a port number. This port number is used on both ends of the transmission so that the right data is passed to the correct application. Port scanning is a process of probing a computer, server or other network host for open ports. It can be used maliciously as a reconnaissance tool to identify the operating system and services running on a computer or host, or it can be used harmlessly by a network administrator to verify network security policies on the network.
Download and launch a port scanning tool like Zenmap. Enter the IP address of your computer, choose a default scanning profile and press ‘scan.’

The scan will report any services that are running, such as web or email services, and their port numbers.
The scan will also report one of the following responses:

‘Open’ or ‘Accepted’ means that the port or service running on the computer can be accessed by other network devices.
‘Closed,’ ‘Denied’ or ‘Not Listening’ means that the port or service is not running on the computer and therefore cannot be exploited.
‘Filtered,’ ‘Dropped’ or ‘Blocked’ means that access to the port or service is blocked by a firewall and therefore it cannot be exploited.
To execute a port scan from outside of your network, you will need to run it against your firewall or router’s public IP address.

Enter the query ‘what is my IP address?’ into a search engine such as Google to find out this information.

Go to the Nmap Online Port Scanner, enter your public IP address in the input box and press ‘Quick Nmap Scan.’ If the response is open for ports 21, 22, 25, 80, 443 or 3389 then most likely, port forwarding has been enabled on your router or firewall and you are running servers on your private network.

Intrusion Detection and Prevention Systems
Intrusion detection systems (IDSs) and intrusion prevention systems (IPSs) are security measures deployed on a network to detect and prevent malicious activities.
An IDS can either be a dedicated network device or one of several tools in a server, firewall or even a host computer operating system, such as Windows or Linux, that scans data against a database of rules or attack signatures, looking for malicious traffic.

An IPS can block or deny traffic based on a positive rule or signature match. One of the most well-known IPS/IDS systems is Snort. The commercial version of Snort is Cisco’s Sourcefire. Sourcefire can perform real-time traffic and port analysis, logging, content searching and matching, as well as detect probes, attacks and execute port scans. It also integrates with other third-party tools for reporting, performance and log analysis.

Software is not perfect. And more than ever before, hackers are exploiting flaws in software before creators get a chance to fix them. When they do this, hackers are said to have carried out a zero-day attack!

The ability to detect these attacks in real time, and stop them immediately, or within minutes of occurring, is the ultimate goal.

Real-Time Detection
Many organizations today are unable to detect attacks until days or even months after they occur.
Detecting attacks in real time requires actively scanning for attacks using firewall and IDS/IPS network devices. Next generation client and server malware detection with connections to online global threat centers must also be used. Today, active scanning devices and software must detect network anomalies using context-based analysis and behavior detection.
DDoS is one of the biggest attack threats requiring real-time detection and response. For many organizations, regularly occurring DDoS attacks cripple Internet servers and network availability. These attacks are extremely difficult to defend against because the attacks originate from hundreds, even thousands, of zombie hosts, and the attacks appear as legitimate traffic.

Protecting Against Malware
One way of defending against zero-day attacks and advanced persistent threats (APTs) is to use an enterprise-level advanced malware detection solution, like Cisco’s Advanced Malware Protection (AMP) Threat Grid.

This is client/server software that can be deployed on host endpoints, as a standalone server or on other network security devices. It analyzes millions of files and correlates them against hundreds of millions of other analyzed malware artifacts for behaviors that reveal an APT. This approach provides a global view of malware attacks, campaigns and their distribution.

Security Best Practices
Many national and professional organizations have published lists of security best practices. Some of the most helpful guidelines are found in organizational repositories such as the National Institute of Standards and Technology (NIST) Computer Security Resource Center.

Perform a risk assessment
Knowing and understanding the value of what you are protecting will help to justify security expenditures.

Create a security policy
Create a policy that clearly outlines the organization’s rules, job roles, and responsibilities and expectations for employees.

Physical security measures
Restrict access to networking closets and server locations, as well as fire suppression.

Human resources security measures
Background checks should be completed for all employees.

Perform and test backups
Back up information regularly and test data recovery from backups.

Maintain security patches and updates
Regularly update server, client and network device operating systems and programs.

Employ access controls
Configure user roles and privilege levels as well as strong user authentication.

Regularly test incident response
Employ an incident response team and test emergency response scenarios.

Implement a network monitoring, analytics and management tool
Choose a security monitoring solution that integrates with other technologies.

Implement network security devices
Use next generation routers, firewalls and other security appliances.

Implement a comprehensive endpoint security solution
Use enterprise level antimalware and antivirus software.

Educate users
Provide training to employees in security procedures.
One of the most widely known and respected organizations for cybersecurity training is the SANS Institute. Click https://www.sans.org/about/  to learn more about SANS and the types of training and certifications they offer.

Encrypt data
Encrypt all sensitive organizational data, including email.
