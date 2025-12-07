# Security Policy

The `CourseVault-Free-Online-Education-Resource-Awesome-List` project maintains the highest standards of integrity and vigilance against security threats. Given its nature as a curated resource list (Awesome List) composed of static Markdown content, our security focus is primarily on **Content Integrity** and **Preventing Malicious Link Injection**.

## 1. Scope of Security Coverage

This policy applies to:

1.  The integrity of the core list files (`README.md`, categorization files) within the repository.
2.  The validation and review process for all third-party links and resources listed in the index.
3.  The minimal GitHub Actions CI/CD pipeline used for list validation (e.g., link checking and markdown linting).

**NOTE:** Since this repository contains no execution code (like Python scripts, JavaScript, or binaries), traditional software vulnerabilities (RCE, XSS on runtime) are not applicable to the repository codebase itself. The primary risk addressed here is the introduction of malicious or phishing links through content contribution.

## 2. Supported Versions

All currently supported branches and versions of the list are hosted on the main repository:

*   **Main Branch:** Supported.

We encourage contributors to ensure they are basing their work off the latest `main` branch state to benefit from the latest security checks and content audits.

## 3. Reporting a Vulnerability or Malicious Content

We deeply appreciate responsible disclosure and work hard to respond quickly to confirmed issues, especially those concerning malicious content injection.

**DO NOT** open a public GitHub Issue for security concerns related to content quality or potential phishing links.

### Preferred Method: Private Disclosure via GitHub Security Advisory

To report a security concern, please use the GitHub Security Advisory feature for private communication with the project maintainers:

1.  Navigate to the **Security** tab of the repository:
    `https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List/security`
2.  Click on **New Draft Security Advisory**.
3.  Provide comprehensive information, including:
    *   A clear, concise description of the vulnerability or malicious link.
    *   The specific file and line number where the issue exists (e.g., `README.md: Line 250`).
    *   If applicable, evidence or steps to reproduce the content issue (e.g., the URL that leads to malicious content).
    *   Your contact information (optional, but appreciated for follow-up).

### Content Integrity Protocol

1.  **Manual Review:** All Pull Requests proposing new links are rigorously reviewed by a maintainer for relevance, quality, and malicious indicators before merging.
2.  **Immediate Removal:** Any listed resource reported as malicious, phishing, or containing inappropriate content will be removed immediately upon verification.

## 4. Security Response Timeline

Our commitment to the community is to provide a swift response and resolution for content integrity issues:

*   **Acknowledgement:** We aim to acknowledge receipt of security reports within **48 business hours**.
*   **Resolution:** For confirmed high-priority threats (e.g., active phishing link), we strive to remove the malicious content and push a remediation commit within **24 hours** of confirmation.

Thank you for helping us keep the CourseVault resource safe and reliable for the global learning community.