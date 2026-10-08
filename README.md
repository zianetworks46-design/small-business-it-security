# small-business-it-security
A practical, plain-English IT security checklist for small businesses: accounts, devices, email, backups, and employee onboarding/offboarding.  

Use it as a quarterly review, share it with your office manager, or hand it to your IT provider as a starting point. Contributions and corrections are welcome.

> **Who this is for:** businesses with roughly 5 to 100 employees, limited or no in-house IT, and a need to protect client data, email, and uptime.

---

## How to use this checklist

1. Copy the checklist into your own document or issue tracker.
2. Mark each item as **Done**, **Partial**, or **Not started**.
3. Fix the **Accounts and Access** and **Backups** sections first. They prevent the most damage for the least effort.
4. Review every quarter, and after any staff change.

---

## 1. Accounts and Access

- [ ] Multi-factor authentication (MFA) is enabled on email, banking, and cloud apps
- [ ] Every employee has their own login (no shared passwords)
- [ ] A password manager is used company-wide
- [ ] Admin accounts are limited to those who need them
- [ ] Admin accounts are separate from everyday user accounts
- [ ] Unused accounts are reviewed and removed

## 2. Email Security

- [ ] Spam and phishing filtering is active beyond the default settings
- [ ] SPF, DKIM, and DMARC are configured for your domain
- [ ] Staff know how to report a suspicious email
- [ ] Payment or bank-detail changes are verified by phone, using a known number
- [ ] Wire transfers require approval from a second person

## 3. Devices and Software

- [ ] Operating systems and apps are updated on a regular schedule
- [ ] No devices run unsupported operating systems
- [ ] Endpoint protection is installed on every computer (ideally EDR, not antivirus alone)
- [ ] Laptops and phones use disk encryption
- [ ] Lost or stolen devices can be locked or wiped remotely
- [ ] An inventory of company devices is kept up to date

## 4. Backups and Recovery

- [ ] Critical data is backed up automatically
- [ ] At least one backup copy is stored off-site or in the cloud
- [ ] Backups are protected from ransomware (separate credentials or immutable storage)
- [ ] A restore test is performed at least twice a year
- [ ] You know how long recovery would take and how much work could be lost
- [ ] There is a written plan for what to do if systems go down

## 5. Network and Wi-Fi

- [ ] Wi-Fi uses WPA2 or WPA3 with a strong password
- [ ] Guest Wi-Fi is separate from the business network
- [ ] The router's default admin password has been changed
- [ ] Router and firewall firmware is kept current
- [ ] Remote access uses a VPN or equivalent secure method

## 6. Employees and Awareness

- [ ] New hires receive basic security training
- [ ] Staff get refresher training or phishing simulations at least yearly
- [ ] Employees know who to contact if something looks wrong
- [ ] There is a clear policy on using personal devices for work
- [ ] Employees are told which apps and AI tools are approved for company data

## 7. Onboarding and Offboarding

**When someone joins:**

- [ ] Accounts are created with least-privilege access
- [ ] MFA is set up on day one
- [ ] Devices are configured and encrypted before handoff
- [ ] Security expectations are covered in orientation

**When someone leaves:**

- [ ] Accounts are disabled the same day
- [ ] Email and file access are transferred or archived
- [ ] Company devices are collected and wiped
- [ ] Shared passwords they knew are changed
- [ ] Access to third-party apps is revoked

## 8. Compliance and Insurance

- [ ] You know which regulations apply to your industry (HIPAA, legal ethics rules, CMMC, etc.)
- [ ] Sensitive client data is identified and access is restricted
- [ ] Cyber insurance requirements are reviewed (insurers often require MFA, backups, and EDR)
- [ ] An incident response contact list is written down and accessible offline

---

## Scoring yourself

| Completed items | What it suggests |
|---|---|
| Most items checked | Strong baseline, so maintain it and review quarterly |
| About half | Gaps exist, so prioritize sections 1 and 4 |
| Few items checked | Treat this as urgent and consider outside help |

This is a general guide, not a complete security assessment. Your needs depend on your industry, size, and the data you handle.

---

## Related reading

- [Business Email Compromise: The Scam Costing Companies More Than Ransomware](https://www.zianetworks.net/blog/business-email-compromise-the-scam-thats-costing-companies-more-than-ransomware/)
- [Onboarding and Offboarding Employees Securely](https://www.zianetworks.net/blog/onboarding-offboarding-employees-securely-the-it-checklist-most-businesses-skip/)
- [Cloud Backup vs Local Backup](https://www.zianetworks.net/blog/cloud-backup-vs-local-backup-which-is-better-for-small-businesses/)
- [What Is EDR and How Is It Different from Antivirus?](https://www.zianetworks.net/blog/what-is-edr-endpoint-detection-response-and-how-is-it-different-from-antivirus/)

## Contributing

Spotted something missing or outdated? Open an issue or submit a pull request. Please keep suggestions practical and written for non-technical readers.

## About

Maintained by [Zia Networks](https://www.zianetworks.net), a managed IT and cybersecurity provider serving small businesses across Albuquerque, Santa Fe, and New Mexico. Learn more about our [managed IT services](https://www.zianetworks.net/services/managed-it-services/) and [cybersecurity services](https://www.zianetworks.net/services/cyber-security/).

## License

Released under the MIT License. You're free to use, copy, and adapt this checklist.
