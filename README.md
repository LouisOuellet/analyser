# Analyser
Watches system logs for key lines

## Functions
### sasl
This functions looks at /var/log/syslog for SASL LOGIN authentication attempts and compiles the IPs in /tmp/ips.list. To stop the execution of the script you can press 'q'. This will trigger the end of the script and you will be prompted to send the report to an email address. The -s option can be use to automatically enter y to the email request.
### vmail_maxUser
This functions looks at /var/log/syslog for vmail authentication attempts that exceeds the max threshold and compiles the accounts in /tmp/accounts.list. To stop the execution of the script you can press 'q'. This will trigger the end of the script and you will be prompted to send the report to an email address. The -s option can be use to automatically enter y to the email request.
