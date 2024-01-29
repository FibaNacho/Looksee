# Looksee
A very basic Python script that performs some common security checks
This script performs the following checks:

Checks for available updates using sudo apt update.
Checks for installed security updates using sudo unattended-upgrade --dry-run --debug.
Checks for open ports using sudo netstat -tuln.
Checks for running services using sudo service --status-all.
Checks for outdated software using sudo apt list --upgradable.
You can run this script on your Linux system, but please be cautious when using sudo as it grants elevated privileges. Make sure you understand the commands you are running and their potential impact on your system.

Keep in mind that a complete security assessment should involve more advanced tools and methodologies, such as vulnerability scanners, penetration testing, and compliance checks, depending on your specific security requirements and objectives. This script serves as a starting point for basic security checks.
