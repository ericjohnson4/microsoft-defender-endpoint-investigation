# Investigation Summary

## Incident Overview

A Microsoft Defender for Endpoint detection validation test was executed to verify endpoint telemetry collection, alert generation, incident correlation, and investigation capabilities within Microsoft Defender XDR.

The validation test generated a Medium severity Suspicious PowerShell Command Line alert, which was automatically correlated into a single security incident.

---

## Investigation Activities

The following activities were performed during the investigation:

* Verified successful endpoint onboarding
* Validated endpoint telemetry generation
* Reviewed Device Timeline activity
* Investigated generated PowerShell alerts
* Examined process execution relationships
* Analyzed incident details within Microsoft Defender XDR
* Reviewed Attack Story Graph entity relationships

---

## Findings

The investigation confirmed that Microsoft Defender for Endpoint successfully detected and recorded the PowerShell-based validation activity.

Microsoft Defender XDR automatically correlated related alerts into a single incident and provided visibility into affected entities, process execution, and attack relationships.

No malicious activity was identified. All alerts resulted from a controlled detection validation exercise.

---

## Conclusion

This investigation demonstrated practical Security Operations Center (SOC) analyst workflows including alert triage, endpoint investigation, incident review, and threat hunting using Microsoft Defender for Endpoint and Microsoft Defender XDR.
