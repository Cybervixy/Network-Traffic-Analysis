# Network-Traffic-Analysis
# **Steps Involved in Capturing and Analyzing Network Traffic for Forensic Purposes**

### **1. Preparation**  
- **Define Scope**: Identify the systems, network segments, and time periods relevant to the investigation.  
- **Legal Permissions**: Ensure compliance with legal requirements for capturing traffic.  

### **2. Network Traffic Capture**  
- **Select Capture Tool**: Use tools like **Wireshark**, **tcpdump**, or **TShark** to collect traffic data.  
- **Capture Location**: Place the capture device in a strategic location within the network, such as at the firewall or gateway.  
- **Filter Traffic**: Apply filters to capture only relevant traffic (e.g., HTTP, DNS, or specific IP addresses).  

### **3. Data Preservation**  
- **Save Raw Data**: Ensure the integrity of the captured traffic (e.g., pcap files) by saving and creating hash values for verification.  
- **Hashing**: Use **MD5** or **SHA-256** to ensure the data hasn't been altered.  

### **4. Initial Traffic Inspection**  
- **Open Capture File**: Use tools like **Wireshark** to view the captured traffic and inspect individual packets.  
- **Apply Filters**: Use display filters to narrow down the analysis (e.g., HTTP, DNS, or TCP filters).  

### **5. Detailed Traffic Analysis**  
- **Identify Hosts**: Analyze the source and destination IP addresses and perform **GeoIP lookups** to locate suspicious IPs.  
- **Follow Network Sessions**: Track full TCP or HTTP sessions to view complete data exchanges.  
- **Protocol Behavior**: Examine how protocols are used and look for anomalies like malformed packets or unexpected communications.  

### **6. Flag Suspicious Traffic**  
- **Use Protocol Anomalies**: Detect misused protocols, such as unexpected DNS or HTTP activity.  
- **Look for Known Malicious Indicators**: Compare IP addresses or domain names against known threat databases.  

### **7. Correlate with Other Evidence**  
- **Combine with Logs**: Compare network traffic with firewall, IDS, or system logs to build a full picture of the incident.  

### **8. Document Findings and Report**  
- Compile all observations and conclusions into a detailed forensic report for documentation or further investigation.

# Thank you

## **Connect with Me**

- [LinkedIn Profile](https://www.linkedin.com/in/victoria-simon-omaojo-9a4586194/)
