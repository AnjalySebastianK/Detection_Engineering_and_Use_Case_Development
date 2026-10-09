# Detection Logic

## Event Patterns
Event patterns are recurring sequences or combinations of activities observed in system logs or telemetry that may indicate suspicious or malicious behavior. They provide context by showing how different events are related over time. For example, multiple failed login attempts followed by a successful login from an unusual location can form a pattern that suggests a brute force attack. Analysts rely on event patterns to distinguish normal activity from abnormal sequences that require investigation.

---

## Behavioral Indicators
Behavioral indicators are signs of malicious activity based on how attackers operate rather than static identifiers. They focus on actions and techniques that adversaries use to achieve their objectives. Examples include unusual PowerShell commands, attempts to disable security tools, or lateral movement across multiple systems. Behavioral indicators are valuable because they highlight attacker intent and can detect threats even when specific signatures or known indicators are absent.

---

## Rule-Based Detection
Rule-based detection involves creating explicit conditions or rules that define when an alert should be triggered. These rules are often based on known attack techniques, compliance requirements, or operational thresholds. For instance, a rule may specify that more than ten failed login attempts within one minute should generate an alert. Rule-based detection is straightforward and effective for identifying predictable threats, but it requires continuous tuning to avoid false positives and to remain relevant as attacker methods evolve.

---

## Risk-Based Detection
Risk-based detection assigns a score or weight to events and alerts based on their potential impact and likelihood of being malicious. Instead of treating all alerts equally, this approach prioritizes incidents that pose the greatest risk to critical assets. Factors such as the sensitivity of the system, the role of the user, and the presence of threat intelligence indicators influence the risk score. For example, a failed login attempt on a domain controller is considered more critical than the same attempt on a test server. Risk-based detection helps security teams allocate resources effectively and focus on the most significant threats.

---

## Detection Effectiveness
Detection effectiveness measures how well detection logic identifies true threats while minimizing false positives and missed incidents. Effective detection balances accuracy, coverage, and operational efficiency. It requires continuous validation, feedback from analysts, and alignment with evolving attacker techniques. Metrics such as detection rate, false positive rate, and mean time to detect are used to evaluate effectiveness. A highly effective detection system ensures that security teams can respond quickly and confidently to genuine threats without being overwhelmed by noise.

---

# Key Takeaways
- Event patterns reveal suspicious sequences of activity across systems.  
- Behavioral indicators highlight attacker techniques and intent beyond static signatures.  
- Rule-based detection uses explicit conditions to trigger alerts for predictable threats.  
- Risk-based detection prioritizes alerts by assigning scores based on impact and likelihood.  
- Detection effectiveness ensures that detection logic remains accurate, reliable, and operationally useful.  
