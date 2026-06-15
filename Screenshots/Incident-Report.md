# Incident Investigation Report

## Incident Summary

A series of failed login attempts were detected on a monitored endpoint.

## Alert Details

- Alert Type: Brute Force Attempt
- Severity: Medium
- Source IP: 192.168.1.100
- Detection Tool: Wazuh

## Investigation Steps

1. Reviewed authentication logs.
2. Identified multiple failed login attempts.
3. Verified no successful unauthorized access.
4. Checked endpoint activity for suspicious behavior.

## Findings

- Multiple failed logins detected.
- No evidence of compromise.
- Activity likely resulted from incorrect credentials or password guessing attempts.

## Recommendations

- Enable account lockout policies.
- Implement MFA.
- Monitor for repeated attempts from the same source.

## Lessons Learned

This investigation improved log analysis and alert triage skills within a SOC environment.
