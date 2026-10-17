# CyberChefcab | Isaac Caballero Cybersecurity Portfolio

[View the live portfolio](https://chefcab001.github.io/isaac-cybersecurity-portfolio/) · [Projects](https://chefcab001.github.io/isaac-cybersecurity-portfolio/portfolio.html) · [Security Research](https://chefcab001.github.io/isaac-cybersecurity-portfolio/research.html) · [Resume Highlights](https://chefcab001.github.io/isaac-cybersecurity-portfolio/resume.html)

## About this portfolio

CyberChefcab documents my transition from 27 years of U.S. Navy service, retiring as a Senior Chief Petty Officer, into cybersecurity engineering, operations, and research. I earned a Bachelor of Science in Information Technology with a cybersecurity specialization from South University, graduating Magna Cum Laude in 2025, and am pursuing a Master of Science in Cybersecurity at Hawaiʻi Pacific University.

This is a **public-facing, evidence-oriented learning and professional portfolio**. It presents practical work, researched security topics, and professional experience while distinguishing observed results from plans, research hypotheses, and third-party findings. It is not a representation of production security certification or independent validation of unpublished systems.

## Featured technical work

| Area | Scope and evidence status | Explore |
| --- | --- | --- |
| **Splunk SOC and security-event ingestion** | Home-lab work involving Debian Linux `rsyslog` forwarding to Splunk Enterprise, Windows telemetry, and observed security events. | [Splunk SOC Lab](splunk-soc-lab.html) |
| **Home-lab security architecture** | Repurposed HP, Lenovo, and Dell systems supporting Linux administration, SIEM analysis, virtualization, and controlled troubleshooting. Planned network segmentation and infrastructure upgrades are identified separately. | [Home Lab](home-lab-architecture.html) |
| **Incident response, DFIR, and GRC** | Public-safe coursework, case studies, evidence-handling practices, control analysis, and documentation. Specific outcomes are described on individual project pages. | [Projects](portfolio.html) |
| **Cloud security and adversarial AI research** | Dated, source-grounded research briefs with engineering lessons, limitations, and explicitly conceptual illustrations. These briefs do not establish that suggested controls have been implemented or tested. | [Research & Intelligence](research.html) |
| **Secure distributed-systems research** | Ongoing defensive laboratory investigation of authorization, cryptographic integrity, and evidence accountability. Private implementation details and unpublished architecture are withheld. | [Public project overview](portfolio.html) |

## Security Research & Intelligence | October 2026

The [research page](research.html) presents two tracks:

- **Cloud Security & DFIR:** Cloud attack-sequence correlation, contextual security findings, and multistage forensic reconstruction. Featured reading discusses AWS GuardDuty Extended Threat Detection and the MotifTrace research paper.
- **Adversarial AI & Trusted Systems:** Why possession of a signing key is not equivalent to authorization, together with research questions about trusted execution boundaries, scope, and provenance.

The page contains two original conceptual illustrations stored in this repository:

- `assets/images/cloud-security-attack-reconstruction.png`
- `assets/images/adversarial-ai-meets-trusted-systems.png`

These images explain security concepts; they are **not screenshots of actual investigations, verified attack paths, or validated enforcement by the private research laboratory**. Original publications remain linked on the research page. The August 2026 cybersecurity briefs are retained as a **dated historical archive**, not represented as current alerts.

## Education and certifications

- **Hawaiʻi Pacific University:** M.S. Cybersecurity, in progress.
- **South University:** B.S. Information Technology, cybersecurity specialization; Magna Cum Laude, 2025.
- **Earned CompTIA certifications:** A+, Network+, Security+.
- **CompTIA CySA+:** Study and exam preparation in progress; **not yet certified**.

Any stackable credentials and framework-alignment statements are described separately from individual earned certifications. No private credential identifiers are published.

## Website structure

| File | Purpose |
| --- | --- |
| `index.html` | Portfolio homepage |
| `portfolio.html` | Technical projects and research overview |
| `splunk-soc-lab.html` | Featured security operations lab |
| `home-lab-architecture.html` | Public-safe lab architecture |
| `research.html` | Cloud/DFIR and adversarial AI research |
| `certifications.html` | Certifications and graduate education |
| `resume.html` | Resume highlights |
| `Isaac_Caballero_Cybersecurity_Resume.html` | HTML resume document; **not a PDF** |
| `contact.html` | Public professional contact routes |
| `404.html` | Custom not-found page |
| `style.css` | Shared layout, typography, and responsive styles |
| `assets/images/` | Site illustrations and other image assets |
| `brief/` | Historical research briefs |

Additional project pages are linked from `portfolio.html`. Individual page menus may be refined as part of subsequent accessibility and navigation work.

## Hosting and security boundaries

The site uses static HTML, CSS, and image assets deployed through **GitHub Pages**, with an `index.html` entry point at the repository root. No application server or server-side database is required for the current portfolio.

Static hosting reduces some server-side application risks but **does not make a site immune to compromise or abuse**. Relevant controls include:

- Account security, multifactor authentication, repository permissions, and protection of Git credentials.
- Careful review of committed source, images, metadata, and outgoing links.
- No publication of API keys, passwords, tokens, private network addresses, client information, or unpublished research internals.
- Appropriate HTTPS deployment, dependency scrutiny if scripts or third-party services are later introduced, and routine link and accessibility checks.
- Clear differentiation between public educational examples and actual observed security evidence.

## Controlled update workflow

Portfolio publication uses a local Git workflow. Changes should be scoped, previewed, and verified before a commit or GitHub push.

1. Inspect the current branch, working tree, and remote baseline.
2. Edit only the approved files; retain unrelated untracked drafts and backups.
3. Verify local HTML links, images, responsive layout, and accessibility.
4. Review content for sensitive information and for unsupported security claims.
5. Stage files by explicit path rather than using `git add .`.
6. Review the staged diff and file allowlist before committing.
7. Push only the approved commit; confirm GitHub Pages has deployed the intended revision.

Validation evidence can include terminal/test output, configurations, logs, screenshots, and reports, with timestamps and context. **Primary observations and reproducible results take precedence over unverified summaries or illustrative diagrams.** A passing local check is not proof of production readiness.

## Contact

Use the [portfolio contact page](contact.html) for public professional contact routes. Private contact details and operationally sensitive information are intentionally excluded.

---

**Portfolio status:** October 2026 public research and professional portfolio refresh. All research findings, project results, and planned work remain subject to the limitations stated on their respective pages.
