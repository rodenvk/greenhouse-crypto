---
title: Green House Crypto Security Policy and Operations
permalink: /security/
---

# Green House Crypto Security Policy and Operations

*Security is our highest priority in operating our nodes. This document outlines our comprehensive security approach and operational practices designed to ensure maximum protection, stability, and uninterrupted performance of our validator infrastructure.*

## Infrastructure Security

### Enterprise-Grade Server Infrastructure
- Dedicated high-performance servers with strict access controls
- Deployed in Tier 3 datacenter with 24/7 security monitoring
- Physical security systems including 24/7 surveillance
- External Network Operations Center (NOC) providing continuous supervision

### Network Security
- Advanced firewall configuration with restrictive rules (default-deny policy)
- Enterprise-grade DDoS protection to mitigate volumetric and application-layer attacks
- Network segregation and isolation of critical validator components

### System Security
- Regular application of security patches and system updates
- Principle of least privilege for all system components
- Comprehensive event logging and security monitoring

## Operational Security

### Key Management
- Hardware security module (Ledger) for all authority keys
- Private keys backups are stored on an encrypted filesystem

### Monitoring and Incident Response
- 24/7 automated monitoring of validator performance metrics
- Real-time alerts for anomalous behavior or security events
- Rapid response protocol for security incidents
- Post-incident analysis and continuous improvement are tracked on our GitHub issues page

### Business Continuity
- Regular encrypted backups of critical validator data
- Comprehensive disaster recovery plan with backup hosting in the US
- Redundant systems and failover capabilities
- Regular testing of recovery procedures

## Security Maintenance

### Update Management
- Prompt application of Solana protocol updates
- Regular security patching schedule
- Validation of Solana client updates Testnet before deploying on Mainnet
- Rollback procedures for failed updates

## Reporting Security Issues

We take all security concerns seriously. If you believe you've found a security vulnerability in our validator operations or have security concerns, please contact us at:

- Email: [admin@greenhouse-crypto.com](mailto:admin@greenhouse-crypto.com)
- PGP Key:

```
-----BEGIN PGP PUBLIC KEY BLOCK-----
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
=3qJO
-----END PGP PUBLIC KEY BLOCK-----
```

Please include the following information in your report:
- Description of the potential issue
- Steps to reproduce (if applicable)
- Potential impact

We commit to:
- Acknowledging receipt of your vulnerability report within 24 hours
- Providing regular updates about our progress
- Not pursuing legal action against security researchers acting in good faith

## Commitment to Security

Our security practices are continuously evolving to address emerging threats and improve our security posture. We are committed to maintaining the highest standards of security in the Solana ecosystem and protecting the integrity of the network.

---
