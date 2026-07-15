Detection
Detect vulnerabilities: A vulnerability is a weakness that an attacker can exploit to carry out things beyond their permission level. A vulnerability might be discovered in any device’s software (operating system and programs), such as a server or computer. For instance, the SOC might discover a set of MS Windows computers that must be patched against a specific published vulnerability. Strictly speaking, vulnerabilities are not necessarily the SOC’s responsibility; however, unfixed vulnerabilities affect the security level of the entire company.
Detect unauthorized activity: Consider the case where an attacker discovered the username and password of one of the employees and used them to log in to the company system. It is crucial to detect this kind of unauthorized activity quickly before it causes any damage. Many clues, such as geographic location, can help us detect this.
Detect policy violations: A security policy is a set of rules and procedures created to help protect a company against security threats and ensure compliance. What is considered a violation would vary from company to company; examples include downloading pirated media files and sending confidential company files insecurely.
Detect intrusions: Intrusions refer to unauthorized access to systems and networks. One scenario would be an attacker successfully exploiting our web application. Another would be a user visiting a malicious site and getting their computer infected.

Project SOC Fundamentals
Project Goal
My main goal was to design and systematize the processes of cyber threat detection within the architecture of a Security Operations Center (SOC). During the work, I focused on establishing a monitoring methodology, classifying information security incidents, and ensuring comprehensive visibility of various attack vectors within the corporate infrastructure.

Project Description
Within the scope of this project, I developed and formalized approaches to detecting suspicious and malicious activity. In my work, I paid special attention to analyzing four key vectors of SOC operations:

Vulnerability Detection: I analyzed the process of monitoring weaknesses in software and operating systems of servers and workstations. I determined that proactively identifying vulnerable nodes (e.g., Windows hosts requiring critical updates) is a fundamental prerequisite for assessing the security posture, even if patch management itself falls outside the direct scope of the SOC.

Unauthorized Activity Detection: I developed mechanisms for the prompt detection of compromised credentials. I structured and described the logic by which the system registers anomalies in account behavior (e.g., atypical login geo-locations) before damage is done to the infrastructure.

Policy Violations: I formulated rules for tracking compliance and adherence to corporate policies by employees. I classified baseline incidents ranging from the unauthorized downloading of pirated content to attempts to transmit confidential data over unsecured channels.

Intrusion Detection: I systematized the indicators of unauthorized access to networks and systems. As part of this task, I studied methods for recording successful web application exploits and detecting endpoint compromise when users interact with malicious links.

Conclusion and Challenges
Completing this project proved to be quite challenging and required a deep dive into architectural and analytical processes. During the work, I came to the conclusion that one of the most time-consuming tasks is fine-tuning the detection logic — I had to understand the mechanisms for minimizing false positives while maintaining high infrastructure visibility.

Furthermore, profiling legitimate activity became a serious challenge for me. I verified in practice that clearly distinguishing between atypical but benign user behavior and actual signs of an attack requires conducting deep contextual analytics and aggregating large volumes of logs.
