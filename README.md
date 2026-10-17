# Isaac Caballero Cybersecurity Portfolio

Public-safe cybersecurity portfolio documenting the transition from 27 years of Navy leadership to graduate cybersecurity education, independent security-laboratory engineering, security operations, network security, incident response, DFIR, GRC, and controlled defensive research. Current academic enrollment: MS Cybersecurity, Hawaiʻi Pacific University (in progress).

## Portfolio Purpose

This repository publishes a static portfolio website that:

- presents cybersecurity projects in a professional format
- highlights certifications and resume-aligned experience
- protects operational security by excluding sensitive details
- emphasizes evidence-backed, public-safe documentation

## Site Structure

Core pages in this repository:

- `index.html` - Home
- `portfolio.html` - Projects
- `certifications.html` - Certifications and current graduate education
- `home-lab-architecture.html` - Public-safe three-system home-lab architecture
- `research.html` - Cloud Security & DFIR and Adversarial AI & Trusted Systems research
- `resume.html` - Resume highlights
- `contact.html` - Public contact routes
- `splunk-soc-lab.html` - Featured project detail
- `Isaac_Caballero_Cybersecurity_Resume.html` - Download-friendly resume page
- `404.html` - Custom not-found page for GitHub Pages
- `style.css` - Shared styling and responsive behavior

## October 2026 Technical Progress

- **Observed lab work:** HP m8530f Debian rsyslog forwarding, Lenovo V15 Splunk Enterprise and Windows telemetry, Dell Inspiron 5400 virtualization/Kali development, and network troubleshooting.
- **Education:** South University BSIT with cybersecurity specialization, Magna Cum Laude (2025); Hawaiʻi Pacific University MS Cybersecurity (in progress).
- **Credentials:** CompTIA A+, Network+, and Security+ earned; CySA+ exam preparation remains in progress.
- **Research:** defensive laboratory work on authorization, cryptographic evidence, and secure distributed systems; internal implementation details are withheld.
- **Planned, not yet completed:** advanced VLAN-capable switching, isolated firewall/routing labs, and higher-capacity virtualization infrastructure.
- **Historical research:** August 2026 briefs are archived records, not current security alerts.

## GitHub Pages Deployment Notes

This site is a static HTML/CSS deployment.

- Deployment target: GitHub Pages
- Entry page: `index.html` at repository root
- Build step: none required
- Asset strategy: relative links to local HTML/CSS files

Recommended deployment settings:

1. In repository settings, enable **Pages**.
2. Select deployment from the repository branch that contains this content (commonly `main`).
3. Use the repository root as the publish source.
4. Validate published navigation, 404 behavior, and external profile links.

## Security and Change-Control Workflow

### Security Rules

- Never publish credentials, tokens, API keys, private IP addresses, or sensitive architecture details.
- Keep all portfolio content public-safe and sanitized.
- Separate verified evidence from interpretation and recommendations.
- Do not claim activities that cannot be supported by available evidence.

### Change-Control Workflow

1. Inspect current files and existing behavior.
2. Propose scoped updates before broad refactoring.
3. Implement targeted changes only.
4. Validate links, accessibility impact, and layout responsiveness.
5. Review diffs before commit.
6. Publish only after confirming public-safe content boundaries.

### Evidence Discipline

Preferred evidence hierarchy:

1. Screenshots
2. Command output
3. Logs
4. Configuration files
5. Reports
6. User notes
