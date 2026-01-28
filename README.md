# Perimeter Security – Firewall Ingress Control Verification

## Executive Summary
This project evaluates Windows Firewall configuration to ensure perimeter security and ingress control are properly enforced. The objective is to verify that firewall profiles are enabled and inbound traffic rules are actively protecting the system. Evidence is documented using screenshots and security validation steps.

## Objectives
- Verify Windows Firewall is enabled across all profiles
- Review inbound firewall rules
- Confirm network protection against unauthorized access
- Document firewall configuration professionally

## Environment
- Operating System: Windows 10 / Windows 11
- Tools Used: Windows Security, Windows Defender Firewall
- Network Profiles: Domain, Private, Public

## Implementation (Step-by-Step)
1. Opened **Windows Security** from the Start menu.
2. Navigated to **Firewall & network protection**.
3. Verified firewall status for:
   - Domain network
   - Private network
   - Public network
4. Confirmed firewall was enabled for all profiles.
5. Opened **Advanced settings**.
6. Reviewed **Inbound Rules** to assess allowed and blocked traffic.
7. Validated firewall enforcement as a perimeter security control.

## Proof of Work
Screenshots demonstrating firewall status and inbound rules are stored in the `/proof` directory, including:
- Firewall profile status
- Advanced firewall rules view

## Diagnostics & Corrective Learning
- No misconfigurations were detected during verification.
- Firewall status validation ensures continued network protection.
- Regular review is recommended to detect unauthorized rule changes.

## Security Impact
- Blocks unauthorized inbound network connections
- Enforces perimeter defense controls
- Reduces exposure to network-based attacks

## Lessons Learned
- Firewall configuration is a foundational security control.
- Active monitoring ensures perimeter defenses remain effective.
- Documentation improves incident response readiness.

## References
- Microsoft Windows Firewall Documentation
- NIST SP 800-41 – Guidelines on Firewalls and Firewall Policy
