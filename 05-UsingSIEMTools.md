# Chapter: Using SIEM Tools

## 1. Introduction

In this chapter, we will explore how **Security Information and Event Management (SIEM)** tools, like **Splunk** and **Chronicle**, help security analysts monitor, detect, and respond to potential security threats. We will break down the types of dashboards available in these tools and explain how they can assist in real-time threat detection, risk analysis, and incident response.

---

## 2. SIEM Tools Overview

### 2.1 Splunk Overview

**Splunk** provides two primary SIEM options: 
- **Splunk® Enterprise**: A self-hosted solution for analyzing and monitoring log data.
- **Splunk® Cloud**: A cloud-hosted version designed for organizations with hybrid or cloud environments.

Both tools offer **dashboard capabilities** to give security professionals insights into an organization’s operational health, security posture, and potential threats by collecting, analyzing, and searching log data across multiple sources.

### 2.2 Chronicle Overview

**Chronicle**, developed by Google, is a **cloud-native SIEM** tool that retains, searches, and analyzes log data. Chronicle offers a series of **dashboards** that help security professionals identify suspicious activities, indicators of compromise (IOCs), and prioritize security incidents based on confidence scores and severity levels.

---

## 3. Splunk Dashboards

Splunk offers several dashboard types designed to address different aspects of security monitoring:

### 3.1 Security Posture Dashboard
- **Purpose**: Designed for **Security Operations Centers (SOCs)**, this dashboard provides a **24-hour overview** of security-related events and trends.
- **Usage**: Analysts can monitor and investigate real-time threats, such as identifying suspicious activity originating from specific **IP addresses**.
- **Example**: Analysts use it to detect abnormal network traffic that could indicate a **breach**.

### 3.2 Executive Summary Dashboard
- **Purpose**: Provides a **high-level overview** of an organization’s security health.
- **Usage**: Analysts present this data to stakeholders to summarize security incidents and trends.
- **Example**: Use it to show the number of incidents resolved over a specific time period to C-suite executives.

### 3.3 Incident Review Dashboard
- **Purpose**: Displays **suspicious patterns** and provides a timeline of events leading up to a security incident.
- **Usage**: Allows analysts to prioritize and investigate **high-risk items** that require immediate review.
- **Example**: A visual timeline of network anomalies just before a **phishing attack** can guide analysts in incident response.

### 3.4 Risk Analysis Dashboard
- **Purpose**: Helps assess risk by analyzing user behavior or network traffic.
- **Usage**: Security analysts can identify users logging in during odd hours or systems experiencing unusually high network activity.
- **Example**: A spike in network traffic from a specific **IP address** during off-hours might indicate **malicious behavior**.

---

## 4. Chronicle Dashboards

Chronicle’s dashboards are designed to help security professionals identify, analyze, and track security threats across various assets:

### 4.1 Enterprise Insights Dashboard
- **Purpose**: Highlights recent alerts and identifies suspicious domain names (IOCs) with **confidence scores**.
- **Usage**: Analysts monitor critical assets like applications or systems, checking for suspicious activity from unusual locations or devices.
- **Example**: Investigate an alert related to multiple login attempts from an unknown **geographic region**.

### 4.2 Data Ingestion and Health Dashboard
- **Purpose**: Tracks the **success rate** of data ingestion, ensuring logs are correctly received.
- **Usage**: Security teams use this dashboard to troubleshoot log-related issues.
- **Example**: Detect errors in log data ingestion that could prevent **timely analysis** of security events.

### 4.3 IOC Matches Dashboard
- **Purpose**: Displays top threats, risks, and vulnerabilities based on domain names, IP addresses, and devices.
- **Usage**: Analysts focus on **high-priority** threats, tracking trends over time.
- **Example**: An IOC match for a known **malicious domain** might prompt further investigation.

### 4.4 Main Dashboard
- **Purpose**: Provides a high-level summary of event activity, data ingestion, and alerting over time.
- **Usage**: Analysts use it to track overall trends, such as failed login attempts or spikes in network traffic.
- **Example**: A sudden increase in failed login attempts could indicate a **brute force attack**.

### 4.5 Rule Detections Dashboard
- **Purpose**: Shows statistics for incidents with the highest occurrences and severities.
- **Usage**: Analysts use this to monitor recurring incidents and create mitigation strategies.
- **Example**: Alerts triggered by users attempting to open known **malicious email attachments**.

### 4.6 User Sign-In Overview Dashboard
- **Purpose**: Monitors user access behavior and detects unusual sign-in activity.
- **Usage**: Identify users signing in from multiple locations simultaneously.
- **Example**: A user account showing **sign-ins** from different countries within a short time frame may indicate a **compromised account**.

---

## 5. Key Takeaways

- **SIEM dashboards** in tools like **Splunk** and **Chronicle** offer powerful insights into an organization’s security posture, incident history, and risk management.
- Analysts use these dashboards to **detect threats**, track **user behavior**, monitor **network traffic**, and prioritize security **incidents**.
- Regularly monitoring and **interpreting dashboard data** enables security teams to respond quickly to high-priority threats, ensuring that risks are mitigated efficiently.
- Later in this course, you’ll have the chance to practice using **SIEM tools**, honing your skills in threat detection and incident response.

---

## 6. Practical Exercises

- **Explore Splunk’s Security Posture Dashboard**: Review security-related events from the last 24 hours and identify any suspicious network activity.
- **Investigate Chronicle’s Enterprise Insights Dashboard**: Analyze alerts related to domain names and assess their impact based on confidence scores.

---

