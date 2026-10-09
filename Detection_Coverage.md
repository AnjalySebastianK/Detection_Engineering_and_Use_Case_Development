# Detection Coverage

## Monitoring Gaps
Monitoring gaps are areas within the environment where security data is not being collected or analyzed. These gaps may occur due to unmonitored endpoints, unsupported applications, or incomplete logging configurations. Attackers often exploit these blind spots to operate undetected. Identifying monitoring gaps ensures that all critical systems and processes are included in the detection strategy, reducing the risk of unnoticed malicious activity.

---

## Visibility Gaps
Visibility gaps occur when collected data does not provide sufficient context to understand what is happening in the environment. For example, logs may show that a process executed but not reveal the parent process or command line arguments. Visibility gaps limit the ability of analysts to investigate alerts effectively. Closing these gaps requires enhancing telemetry sources, enabling detailed logging, and integrating multiple data streams to provide a complete picture of system activity.

---

## Risk Prioritization
Risk prioritization is the process of focusing detection efforts on the most critical assets, threats, and attack techniques. Not all systems or events carry the same level of risk, so prioritization ensures that resources are allocated where they matter most. For instance, monitoring domain controllers, financial systems, or sensitive databases should take precedence over less critical servers. Prioritization helps SOC teams balance coverage with efficiency, ensuring that high-impact threats are detected quickly.

---

## Coverage Analysis
Coverage analysis evaluates how well detection rules and monitoring capabilities align with organizational needs and threat models. It involves mapping detections to frameworks such as MITRE ATT&CK, identifying which techniques are covered, and measuring the depth of detection logic. Coverage analysis highlights strengths, weaknesses, and overlaps in detection capabilities. This structured evaluation allows teams to plan improvements and track progress toward comprehensive coverage.

---

## Detection Strategy
Detection strategy defines the overall approach to achieving strong coverage across the environment. It combines monitoring, visibility, prioritization, and analysis into a coherent plan. A well-defined strategy ensures that detection engineering efforts are aligned with business objectives, threat intelligence, and operational capacity. The strategy should emphasize continuous improvement, integration of new data sources, and adaptation to evolving adversary techniques. By following a clear detection strategy, organizations can maintain resilience and minimize blind spots.

---

# Key Takeaways
- Monitoring gaps represent unmonitored areas that attackers may exploit.  
- Visibility gaps limit the depth of understanding in collected data.  
- Risk prioritization ensures focus on high-value assets and critical threats.  
- Coverage analysis evaluates detection alignment with frameworks and threat models.  
- Detection strategy integrates all elements into a coherent plan for resilient defense.  
