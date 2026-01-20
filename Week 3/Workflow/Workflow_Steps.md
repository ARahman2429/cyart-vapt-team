# VAPT Workflow – Week 3

This document describes the step-by-step workflow followed during the Vulnerability Assessment and Penetration Testing (VAPT) capstone project.

---

## Step 1: Reconnaissance and Discovery
- Identified target IP and exposed services
- Discovered open ports and running services
- Noted outdated software versions

## Step 2: Vulnerability Identification
- Reviewed discovered services for known vulnerabilities
- Prioritized vulnerabilities based on risk and impact
- Selected Apache Remote Code Execution as primary target

## Step 3: Exploitation (Controlled)
- Performed controlled exploitation of the web service
- Gained limited system access for validation
- Avoided excessive exploitation

## Step 4: Post-Exploitation Validation
- Verified current user and privilege level
- Confirmed potential impact
- Did not create persistence or modify system state

## Step 5: Evidence Collection
- Collected minimal proof of exploitation
- Captured system context and limited traffic
- Generated hashes to ensure integrity

## Step 6: Clean Exit
- Terminated all active sessions
- Removed temporary artifacts
- Ensured no backdoors or persistence remained

## Step 7: Reporting
- Documented findings with severity and CVSS
- Prepared executive and technical summaries
- Provided remediation recommendations
