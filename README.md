# DFE-Attack-Simulation

## Objective
The Objective of the Lab are to: 
- Simulate malicious activity to trigger Defender alerts

- Analyze alerts and timelines in Defender for Endpoint

- Isolate a compromised endpoint to contain a threat

- Perform remote investigation using Live Response

- Understand how these actions map to SOC and IR workflows

### Step 1: Verify Device Onboarding 
1- log in to Microsoft Defender Portal
2- Go to Assets, Devices
3- Confirm that Test endpoint shows Onboarded, has recent activity.
This will confirms the endpoint is reporting telemetry to Defender.

### Step 2: Simulate and Attack (Detection Phase)
1- In the test endpoint I execute the
   - PowerShell Command
2- In Defender Portal, I was able to see
   - The Alerts
     
Refer to Screenshot 1 

### Step 3: Analyze the Alert & TimeLine
1- In Incident portal, I was able to see that there is a
   - Suspicious Application Discover
   - Suspicious System Network Connections Discovery
   - Unexpected behavior observed by a process ran with no command line arguments with date and time

Refer to Screenshot 2

### Step 4: Isolate the Device (Containment Phase)
I was able to successful isolate the device affected to:
- Contain the threats
- Prevent malware or attackers from spreading across the network
- Minimize the damage, and preserve the infected device for forensic investigation

Refer to Screeshot 3, and 4

### Step 5: Initiate Live Response (Investigation Phase)
1- Start Live Response
2- Run investigation commands

### Step 6: Validate Findings & Respond
1- I am able to confirm malicious process behavior
2- Detection Method
3- Timeline evidence
4- Response Actions take

### Skills Learned

- Advanced understanding End-to-end incident response workflow
- Analyzing Behavior-based threat detection
- Rapid containment using isolation
- Remote Forensic investigation

### Tools Used

- KQL (Advanced Hunting) - Query endpoint telemetry
- Microsoft Defender for Endpoint (MDE/DFE)
- Microsoft Sentinel - SIEM correlation and Escalation
- PowerShell - Used for benign attack simulations
- Azure Virtual Machines - Lab environment hosting endpoints

### Lesson Learned
- Detection alone is not enough - Response speed and accuracy matter
- Device Isolation is a powerful containment control in active incidents
- Live Response enables stealthy, real-time investigation
- These practices align with NIST 800-61 Incident Response and MITRE ATT&CK frameworks

### Screenshots
# Screenshot 1 - Simulate and Attack


<img width="1604" height="484" alt="image" src="https://github.com/user-attachments/assets/33fcdd2f-1ac8-4854-a4ee-594c2d472ffa" />

# Screenshot 2: Analyze the Alert & TimeLine

<img width="1251" height="851" alt="image" src="https://github.com/user-attachments/assets/c4862979-1dfd-44e5-9766-79ce9e98c16f" />

# Screenshot 3, 4: Isolate the Device (Containment Phase)

<img width="1633" height="899" alt="image" src="https://github.com/user-attachments/assets/35491cba-19ca-44ae-8c19-f6f96295541d" />

<img width="1631" height="900" alt="image" src="https://github.com/user-attachments/assets/9298ea2c-3bff-4cdb-b14c-978dc63b97d3" />



