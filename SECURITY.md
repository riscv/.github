# RISC-V International Security Vulnerability Reporting Policy

We at **RISC-V International**, along with our global community of contributors, work to develop secure, open-standard specifications and associated software implementations. We also work to secure the infrastructure and processes we use to manage the ISA (Instruction Set Architecture) lifecycle.

We value the work of security researchers. If you discover a security vulnerability in a RISC-V specification, a strategic open-source project managed by RISC-V International, the ISA, or our infrastructure, please let us know immediately.

## Where to Report

You can privately report any security vulnerabilities found with the ISA or RISC-V International infrastructure to **security@riscv.org**. 
- **For RISC-V Infrastructure:** If you find a vulnerability in the main RISC-V website or member portal, privately report it to **security@riscv.org**. 

For security vulnerability in a specific RISC-V hardware implementation, specification, or software, please report it directly to that group using their reporting process if possible.

## What Not to Report

Do not send reports for specific architectural extensions outside of those defined by the RISC-V International ISA, third-party hardware implementations, or software issues such as the Docker, KVM, or the kernel. We will do our best to work with you, but we do not control the implementation details of hardware or software. That said, if you are unsure about a specific security issue, it is acceptable to reach out, and we will do our best to direct you to the appropriate community when we are able.

## Guidance for Reporters

The reporting process is typically found in the SECURITY.md file of the relevant GitHub repository and may also be found on the **RISC-V Technical Wiki**.

1. **Email:** Reports go to security@riscv.org. For example, vulnerabilities in the definitions of RISC-V profiles or extensions should be directed to this address. It is advised to encrypt the content of the email with riscv_security_pub.pem key.
2. **Ambiguity:** If it is unclear how to report a vulnerability for a specific RISC-V project, contact **security@riscv.org** for clarification.
3. **Timeline:** We ask for a standard **90-day window** to develop a mitigation or update the specification before the vulnerability is made public.

**Note for Security Researchers:** Please consult the **OpenSSF "Guidance for Security Researchers"** if you are new to coordinated disclosure. Automated data dumps (fuzzers/static analysis) without a proof-of-concept are generally not considered valid reports.

---

## For Task Group Chairs and Maintainers

If you lead a **RISC-V Task Group** or maintain a project under the RISC-V umbrella, we ask that you:
- Maintain a clear SECURITY.md file in your repository in coordination with RISC-V International.
- Be prepared to coordinate with the **Security HC** to ensure architectural flaws are addressed across the ecosystem.
- Give public credit to the researcher (unless they request anonymity) once a fix or architectural update is ratified.

We also encourage all contributors to follow the **RISC-V Security Model** and utilize resources from the **Open Source Security Foundation (OpenSSF)** to ensure our open standard remains the most secure ISA in the world.

## Legal and Acceptable Research

RISC-V International cannot provide legal advice; it is your responsibility to comply with local laws regarding security research. However, **RISC-V International will not pursue legal action** against individuals who perform good-faith security analysis on our specifications or projects and disclose them via our defined coordinated disclosure processes.

