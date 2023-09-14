# Cybersecurity

- Cyber Security
    
    It is a practice of protecting systems & networks from Digital Attacks.
    
    Following are the types of Cyber security :
    
    1. Network Security
    2. Information Security
    3. Application Security
    4. Cloud Security
    5. IOT Security
    6. Mobile Security
- Reference Model
    
    A standard framework that ensures clear communication between networks.
    
    Types :
    
    - OSI
        
        There are 7 inter-linked layers
        
        1. Physical Layer - responsible for physical connection between devices. The information is stored in the form of Bit and sends data to datalink layer.
        2. Data Link layer - responsible for transmitting data from one node to another. It is also responsible for converting data packets into received from network layer to frames - packets in data link layer
        3. Network layer - responsible for transferring data from one host to other in different networks. it is responsible for routing and logical addressing. Routing is used to find the shortest path for transmitting the data & logical addressing is the method is used to identify devices in the network.
        4. Transport layer - responsible to provide end to end communication between 2 devices. Provides service to application layer and receives service from network layer
        5. Session layer - responsible for establishing connection, maintaining & authentication of sessions
        6. Presentation or translation layer - responsible for translation, encryption, decryption and compression
        7. Application layer - only layer that directly interacts with the data from the end user
    - TCP/IP
        
        TCP - Transmission Control protocol
        
        IP - Internet protocol
        
        There are 4 layers
        
        1. Network access layer : it is the combination of physical layer and datalink layer from OSI Model and is responsible for transmission of layer over the network
        2. Internet or Network layer : responsible for logical transmission of data over network, the main protocol used here is IP Protocol. It also ensures that the data packets reaches the destination independently.
        3. Transport layer : responsible for error free transmission of data to destination. TCP & UDP protocols are used in this layer
        4. Application layer : handles all high level protocol. Directly interacts with the data from the end user
- Network Security
    
    It is the process of taking precautionary measures to protect the device from unauthorised access, modification and destruction.
    
- Difference between Cyber Security and Network Security
    
    
    | Cyber Security | Network Security |
    | --- | --- |
    | Cyber Security protects the data residing in the devices or servers in a network. | Network Security protects the data flowing over the network. |
    | Protects from Cyber Attacks. | Protects from DOS Attacks. |
    | It deals with the protection of digital data. | It Deals with the protection of transit data. |
    | It protects the data which is resting. | It protects the data flowing across the network through terminals. |
- Types of Attacks
    
    
    | Active Attack | Passive Attack |
    | --- | --- |
    | A security attack where the attacker alters the message. | A security attack where the attacker observes and uses the content of the messages to perform various malicious activities. |
    | The victim gets to know once the attack is performed. | The victim here is unaware. |
- Types of Network Safety Attacks
    - Data Threat
        
        It occurs when the attacker uses a system without the consent of the owner to gain private information such as login info. Data Threat is similar to Data Theft.
        
    - Insider Threat
        
        This occurs by the employee of the org. The employee might misuse his/ her login credentials to penetrate into the network to gain confidential data from the org system.
        
    - Malware Attack
        
        It is done my inserting malicious code into the device.
        
    - Password Attack
        
        It is unethically trying to enter into a system by guessing or cracking the password.
        
    - Social Engineering
        
        The attacker might try to psychologically manipulate the user to gain private information or security protocols.
        
- Network Vulnerabilities
    
    Network Vulnerabilities are weakness in a computer system that might become an entry point for hackers to attack the entire network.
    
    Few common network vulnerabilities
    
    1. Improperly installed hardware or software
    2. Operating Systems that have not been updated
    3. Complete lack of physical security
    4. Insecure passwords or weak passwords
    5. Design flaws in a network
    6. Outdated or Unpacked software applications
    7. Checking the firewall configuration for latest version
    8. Mobile device vulnerabilities
- Tools used to ensure network security
    
    Following are tools to ensure Network Security
    
    - Packet Crafters
        
        These are used by the network admins to find out loopholes in the network and check the behaviour of devices in the network
        
    - Web Scanners
        
        These are used to find the vulnerabilities in web servers, proxy servers and web application servers.
        
    - Packet Sniffers
        
        Also known as Package Analyser, Protocol Analyser or Network Analyser. It is hardware or software used to monitor the network traffic. They also analyse the data packets transmitted over the network.
        
    - Intrusion Detection System
        
        It is designed to detect all the malicious activities carried out in the network and also sends alert messages.
        
    - Penetration Testing Software
        
        It is used to perform penetration tests. Penetration testing is the process of exploiting the system vulnerabilities to enhance the overall security of system. It is also known as bend test or ethical hacking.
        
- Network Security Protocols
    
    Network Security Protocols ensure to maintain the security and integrity of data while being transmitted over the network.
    
    Following are the 5 major Network Security Protocols
    
    - TLS/SSL
        - TLS - Transport Layer Security
            
            It is an upgraded version of SSL. It is one of the most popular & secure encryption protocols.
            
            It includes 2 layers
            
            - Handshake protocol
                
                It is responsible to initiate a secure connection between the client and server. The client and the server authentication each other and select an encryption algorithm. They also generate a shared key using public key encryption.
                
                TLS doesn’t perform encryption process all alone, it uses encryption algorithms like RSA, AES etc to encrypt the communication.
                
            - Record Protocol
                
                It is responsible for securely transferring data packets between the client and server using shared keys generated during the Handshake protocol.
                
        - SSL - Secure Sockets Layer
            
            
    - IPsec
        
        IPsec stands for Internet Protocol Security and is commonly used in VPN. VPN is Virtual Private Network used for transferring data into a network via Internet connection. It hides the IP Address of the server, and redirects the server where VPN Host handles it.
        
        IPsec is used with Encryption Algorithms such as : DDDES, AES etc.
        
        It is fast and easy to implement. It is implemented in two modes.
        
        1. Tunnel Mode - In Tunnel Mode both the payload and header are encrypted and sent in a new packet with another header.
        2. Transport Mode - Here only the payload is encrypted and not the header.
    - SSH
        
        SSH stands for Secure Shell.
        
        It works similar to VPN. In SSH an encrypted tunnel is created for transferring files. The SSH works in three levels.
        
        1. Transport Level - Responsible for establishing a secure connection between two parties, authenticating them and encrypting data.
        2. Authentication Level - Here the client authenticates its identity using authentication methods specified by the server at transport level.
        3. Connection Level - Responsible for handling all the connections between servers and the client. 
    - PGP
        
        Stands for Pretty Good Privacy. Actual name - Open PGP.
        
        It is used with encryption algorithm such as DDDES, AES, TooFish, RSA etc.
        
        PGP allows users to encrypt the data and digitally sign over it to ensure that it is authenticated. It also ensures integrity and is mainly used to secure confidential email information.
        
    - HTTPS
        
        Stands for Hyper Text Transfer Secure. This protocol is used to transfer the data securely between the web browser and the web server. It is a secure extension of HTTP, which is certified by the Server Socket Layer.
        
- Types of Network Security Solutions
    
    Following are the 8 different types of Network Security Solutions
    
    - Stateful Inspection Firewall
        - What is Firewall ?
            
            Firewall is a network security device that monitors all the incoming and outgoing traffic and permits, blocks or drops the data packet based on a defined set of security rules.
            
            It establishes a barrier between your internal network and the incoming traffic from an untrusted source such as the internet to block the malicious traffic such as viruses and hacking.
            
            A firewall can be implemented either as a software or a hardware device though it is best to have both.
            
            A software firewall is a program that is installed on your computer to regulate traffic through applications or port numbers.
            
            A hardware firewall is a physical device which is installed between you network and gateway. A gateway is an networking hardware device that acts as a gate to form a passage between two network devices with two high level protocols.
            
        
        The Stateful Inspection Firewall is also known as Dynamic Packet Filtering.
        
        This firewall accepts or blocks the data packets depending upon the state port or protocol information.
        
        All the session information like the IP Addresses and Port Numbers are already recorded for better security.
        
        The Stateful Inspection Firewall monitors each and every connection to check if the connection is genuine.
        
        This type of firewall is used in business environment. It verifies each and everything inside the data packets while filtering it.
        
    - Network Segmentation
        
        Network Segmentation is dividing the network into segments to enhance the performance and security.
        
    - Multi-Factor Authentication
        
        It means to authenticate the user in multiple steps. It is the 2 Factor Authentication.
        
    - VPN
        
        It is a secure private network which allows user to send the data from a device to a network over the internet.
        
    - Encryption
        
        The process of scrambling the data such that only the authorised users can access the data using encryption key.
        
        An encryption key is a string of characters used in an algorithm to convert plain text (unencrypted data) to cypher text (encrypted data). The encryption is required to ensure confidentiality and integrity.
        
    - Intrusion Behaviour System
        
        It identifies vulnerabilities in a network.
        
    - Web Filtering
        
        It is to prevent users to view certain websites that are blocked by the web browser.
        
    - Anti-virus
        
        It is a software that prevents computer system from malware.
        
        Example : Norton. Avast. CasperSky.
        
- Network Security best practices for Businesses
    - Network Audit
        
        The goal of network audit is to identify
        
        1. the backups,
        2. open codes, 
        3. antivirus and anti malware softwares, 
        4. the overall strength of firewall, 
        5. the overall health of server, softwares and applications, 
        6. the possibilities of security vulnerabilities etc
        
        The output from Network Audit will help the Network Admin to make improvements.
        
    - Disable File sharing
        
        File sharing being a convenient features is also the most vulnerable method for attacks. Hence it is recommended to disable the file sharing for all the employees devices except the independent servers.
        
    - Setup a firewall
        
        It is advisable to setup a firewall in all devices in e-commerce businesses as it helps to protect the confidential information of customers.
        
    - Invest in a VPN
        
        It is always good for companies to invest in a VPN. As it blocks all the browser history data, personal information from the hackers and it also encrypts the data which ensures the privacy of all its users.
        
    - Securing your router
        
        Securing your router is essential as security breaches can occur just by hitting reset button on your network router. Place it in a secure location and update network name frequently. Also use private IP address.
        
        Make sure to establish a security maintenance system that always reminds you to checklist on the security to-do’s such as changing the password after certain period, monitoring network access history, running activity reports, updating software and regular backups.
        
        It is also important to train the employees to understand the complication and safety measures needed to be taken to ensure network safety.
        
- What certifications you can get in Cybersecurity
    1. CEH
    2. CISSP
    3. CompTIA:Security+
    4. CISM
    5. CompTIA:Network+