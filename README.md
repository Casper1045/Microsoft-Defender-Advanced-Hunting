# Microsoft-Defender-Advanced-Hunting
Information and practical action learned from my experiences with Microsoft Defender Endpoint Protection

1-Advanced Hunting - SCID.csv
Contains Secure Configuration Assessment for Device in company. Coming from a query (Advanced Hunting)

SCIDs (Secure Configuration IDs) are unique identifiers assigned to specific security configurations or controls within a device's security posture. Each SCID corresponds to a critical security setting, such as:

SCID-2000 (SensorEnabled):
Ensures the security sensor is enabled on the device, allowing it to collect and report telemetry data critical for threat detection.

SCID-2001 (SensorDataCollection):
Verifies that the sensor is actively collecting data necessary for security monitoring, enabling real-time detection and response to threats.

SCID-2002 (ImpairedCommunications):
Detects issues with device communication to the central security platform, such as connectivity or firewall blocks, which could impede data flow or updates.

SCID-2003 (TamperProtection):
Prevents unauthorized changes to security configurations, ensuring critical settings remain intact to defend against tampering by attackers.

SCID-2010 (AntivirusEnabled):
Confirms that antivirus software is installed, active, and functioning correctly to detect and block malware.

SCID-2011 (AntivirusSignatureVersion):
Checks if the antivirus signatures are up to date, ensuring the latest threat definitions are available to detect emerging malware variants.

SCID-2012 (RealtimeProtection):
Ensures real-time protection is enabled, allowing the system to monitor and respond to threats as they occur, rather than relying solely on periodic scans.

SCID-91 (BehaviorMonitoring):
Verifies that behavioral monitoring is active, enabling the detection of suspicious activity based on behavior patterns rather than just known signatures.

SCID-2013 (PUAProtection):
Confirms protection against potentially unwanted applications (PUAs), which, while not outright malicious, can pose security or privacy risks.

SCID-2014 (AntivirusReporting):
Verifies that the antivirus solution is reporting its status and activity to the central management platform for monitoring and compliance purposes.

SCID-2016 (CloudProtection):
Ensures cloud-delivered protection is active, leveraging cloud-based intelligence for faster threat detection and response to the latest attacks.

Importance of Monitoring All These SCIDs:
Each SCID addresses a critical component of device security. Together, they form a comprehensive framework to ensure devices are:

Properly monitored through sensors and real-time data collection.
Actively protected via antivirus, behavioral monitoring, and cloud intelligence.
Resilient to tampering with safeguards like TamperProtection.
Prepared for emerging threats with up-to-date signatures and cloud-based defenses.
