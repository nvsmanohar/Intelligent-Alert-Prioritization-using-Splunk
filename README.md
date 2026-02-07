# Intelligent-Alert-Prioritization-using-Splunk
This project  proposes an explainable alert prioritization framework that integrates a Technical Risk Score with a novel Stress Score to account for alert repetition
# Abstract 
Security Information and Event Management (SIEM) systems generate an overwhelming number of alerts, leading to alert fatigue and delayed inci- dent response. Existing SIEM solutions primarily rely on severity based risk scores, neglecting alert frequency. This paper proposes an explainable alert prioritization framework that integrates a Technical Risk Score with a novel Stress Score to account for alert repetition. A mathematical scoring model and rule based prioritization mechanism dynamically adapt to burst alert conditions. The approach is implemented in Splunk and evaluated using real time system logs and large scale synthetic datasets. Experimental results show an estimated alert reduction of 65% and analyst time savings of up to 83%, demonstrating improved alert handling efficiency. The proposed framework is transparent, scalable, and suitable for practical SOC deployments.
# Objectives
•	A mathematically formulated alert scoring model that integrates Technical Risk Score and Stress Score to prioritize security alerts based on both severity and frequency.
•	A transparent and explainable rule based alert prioritization mechanism, enabling analysts to clearly understand why an alert is assigned a specific priority level.
•	A dynamic alert prioritization strategy that adapts alert scores under high alert volumes and burst conditions, effectively addressing alert fatigue.
•	A practical SIEM-based implementation using Splunk, validated on both real-time system logs and large-scale synthetic datasets.
# Tools and Technologies
Search Processing Language is used in this project for writing queries
Splunk Universal Forwarder is used to collect data from different clients
Splunk Enterprise Edition is used by admin to process information and display the results
# Methodology
Traditional SIEM systems primarily rely on technical risk scores to determine the severity of security alerts. While such severity-based scoring mechanisms are useful for identifying potentially harmful events, they do not sufficiently account for the frequency at which alerts occur. As a result, repeated alerts generated within a short time interval may not receive adequate priority, even though they often indicate ongoing attack activities. To overcome this limitation, the proposed methodology integrates both Risk Score and Stress Score to achieve more effective and operationally meaningful alert prioritization.
The proposed framework introduces a frequency aware and explainable alert scoring mechanism that enables security analysts to prioritize alerts based on both severity and frequency. By incorporating Stress Score along side traditional Risk Score, the system captures the cumulative operational impact of repeated alerts, thereby addressing alert fatigue and improving incident response efficiency. The overall methodology is designed to be transparent, rule-based, and easily deployable within existing SIEM infrastructures.
# Result
Experimental evaluation using real-time security logs and synthetic datasets demonstrates improved alert handling efficiency and a significant reduction in analyst workload, confirming the practical suitability of the proposed framework for deployment in enterprise Security Operations Center (SOC) environments.
