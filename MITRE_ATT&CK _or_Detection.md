# MITRE ATT&CK for Detection

## ATT&CK Techniques
ATT&CK techniques describe the specific methods adversaries use to achieve their objectives during an attack. Each technique represents a concrete action, such as credential dumping, phishing, or command-line execution. Techniques are organized under tactics, which represent the adversary’s goals. By studying techniques, defenders gain insight into how attackers operate and can design detection rules that directly target these behaviors.

---

## ATT&CK Mappings
ATT&CK mappings involve aligning detection rules, alerts, and threat intelligence reports with the techniques defined in the ATT&CK framework. This process creates a common language between defenders, tools, and researchers. For example, a detection rule for suspicious PowerShell activity can be mapped to the technique “Command and Scripting Interpreter.” Mappings ensure that detections are structured, comparable, and traceable to known adversary behaviors.

---

## Coverage Assessment
Coverage assessment is the process of evaluating how well an organization’s detection rules and monitoring capabilities align with ATT&CK techniques. It identifies which techniques are covered, partially covered, or not covered at all. This assessment highlights strengths and gaps in detection capabilities. For instance, an organization may have strong coverage for credential access techniques but weak coverage for lateral movement. Coverage assessment helps prioritize improvements and resource allocation.

---

## Threat-Informed Detections
Threat-informed detections are rules and alerts designed with direct reference to adversary tactics, techniques, and procedures (TTPs). Instead of relying solely on generic indicators, these detections are built to recognize behaviors attackers are known to use. For example, detections may focus on persistence techniques such as scheduled tasks or registry modifications. Threat-informed detections improve accuracy and relevance by ensuring that monitoring aligns with real-world threats.

---

## Detection Gaps
Detection gaps are areas where existing monitoring and rules fail to identify adversary techniques. These gaps may occur due to missing data sources, lack of visibility, or incomplete rule coverage. Identifying detection gaps is critical because attackers often exploit blind spots to remain undetected. Addressing gaps involves enhancing telemetry collection, creating new rules, and refining existing detections to ensure comprehensive coverage across the ATT&CK matrix.

---

# Key Takeaways
- ATT&CK techniques define specific adversary actions that defenders must detect.  
- ATT&CK mappings align detection rules with standardized techniques for consistency.  
- Coverage assessment evaluates how well detections address the full spectrum of adversary behaviors.  
- Threat-informed detections are built directly from known attacker tactics and techniques.  
- Detection gaps highlight blind spots that must be addressed to strengthen overall defense.  
