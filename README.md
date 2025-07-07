# Hash Comparison Lab – Cybersecurity Activity

As a security analyst, you’ll need to implement security controls to protect organizations against a range of threats.
That’s where hashing comes in. Previously, you learned that a hash function is an algorithm that produces a code that can’t be decrypted. Hash functions are used to uniquely identify the contents of a file so that you can check whether it has been modified. This code provides a unique identifier known as a hash value or digest.
For example, a malicious program may mimic an original program. If one code line is different from the original program, it produces a different hash value. Security teams can then identify the malicious program and work to mitigate the risk.
Many tools are available to compare hashes for various scenarios. But for a security analyst it’s important to know how to manually compare hashes.
In this lab activity, we’ll create hash values for two files and use Linux commands to manually examine the differences.


## Overview
This project simulates a common task for security analysts: manually comparing hash values of files to detect changes or tampering.

## Scenario
Hash functions are used to detect if a file has been modified. If two files produce different hash values, one has likely been changed.

In this lab, we:
- Create two text files (`file1.txt` and `file2.txt`)
- Use Linux commands to generate and compare their hash values

## Commands Used
```bash
sha256sum file1.txt
sha256sum file2.txt
diff file1.txt file2.txt

