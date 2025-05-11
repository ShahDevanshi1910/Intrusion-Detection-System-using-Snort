# Intrusion Detection System using Snort (IPv4)

This project implements an Intrusion Detection System using **Snort** to monitor and secure a university's IPv4 network during exams, hackathons, and daily operations. It detects and blocks cheating attempts, malicious activities, and unauthorized access to online resources.

## Features
- **Cheating Detection**: Blocks access to sites like GeeksforGeeks, Gmail, ChatGPT, YouTube, Google, and JavaTpoint during exams.
- **Local Rules**: Custom rules to enforce exam restrictions and monitor unusual student behavior.
- **Malicious Activity Detection**: Identifies and alerts on any suspicious or malicious attempts within the network.
- **Backdoor & App Rules**: Detects remote access tools, unauthorized applications, and suspicious port usage.
- **SMTP Rules**: Flags suspicious email traffic and potential data leaks.
- **DDoS Detection**: Detects SYN floods, ICMP floods, and unusual traffic bursts.
- **File Download Control**: Monitors bandwidth to detect and flag large or potentially harmful file download.
