# Jiya-Daulat-Task-4
Configured and tested Windows Firewall rules by blocking inbound traffic on Port 23 (Telnet), verifying the rule, and restoring the original configuration to understand basic firewall security and traffic filtering.

# Objective

The objective of this task was to understand how a firewall works by viewing existing firewall rules, creating a rule to block a specific port, testing the rule, and removing it after verification.

##Tools Used

* Windows Defender Firewall with Advanced Security
* Command Prompt (CMD)
* Windows Operating System

# Steps Performed

# 1. Opened Windows Firewall

The Windows Firewall configuration tool was opened using:

```text
wf.msc
```

# 2. Viewed Existing Firewall Rules

Navigated to **Inbound Rules** and reviewed the existing firewall configurations.

# 3. Created a Rule to Block Port 23

A new inbound rule was created with the following settings:

* Rule Type: Port
* Protocol: TCP
* Port Number: 23
* Action: Block the Connection

Rule Name:

```text
Block Telnet Port 23
```

# 4. Tested the Firewall Rule

The firewall configuration was verified by checking that the rule was successfully added to the inbound rules list.

# 5. Removed the Test Rule

After testing, the rule **Block Telnet Port 23** was deleted to restore the original firewall configuration.

 Screenshots Included

1. Existing Inbound Rules
2. Block Port 23 Rule Creation
3. Block Port 23 Rule Added
4. Firewall Rule Verification
5. Rule Deletion

# Results

* Successfully viewed existing firewall rules.
* Successfully created a rule to block inbound traffic on port 23.
* Verified that the rule was active.
* Successfully removed the rule after testing.


## Conclusion

This task provided hands-on experience with Windows Firewall configuration. Firewall rules were created, verified, and removed successfully, demonstrating how firewalls control network traffic and improve system security.
