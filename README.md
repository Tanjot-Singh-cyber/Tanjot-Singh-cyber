<h1 align="center">Tanjot Singh</h1>

<p align="center">
  Application Security · CVE Author · B.Tech CSE '28 @ MIET Jammu
</p>

<p align="center">
  <a href="https://linkedin.com/in/tanjot-singh-69579a352">LinkedIn</a> ·
  <a href="https://github.com/Tanjot-Singh-cyber/gigcash-web-security">AppSec Portfolio</a>
</p>

---

### About

Self-directed AppSec researcher focused on web application vulnerabilities — API security, GraphQL, authentication flaws, and server-side bugs. I work through real targets on HackerOne and open-source CVE hunting alongside my B.Tech CSE degree.

Not chasing certifications. Building proof-of-work.

---

### Security Findings

| # | Finding | Target | Severity | Status |
|---|---------|--------|----------|--------|
| 1 | SSRF — unvalidated URL parameter allows internal network requests | Blombooru (FastAPI) | **High** (CVSS) | [GHSA-5c5w-x8jp-fjqw](https://github.com/advisories/GHSA-5c5w-x8jp-fjqw) · CWE-918 |
| 2 | IDOR/BOLA — GraphQL query accepts cross-user UUIDs without auth rejection | subspace.money | Medium | Reported via Bugbase |

---

### Projects

#### [HeaderGuard](https://github.com/Tanjot-Singh-cyber/headerguard)
HTTP security header analyzer built in Python/Flask. Scans real targets, detects weak configs, outputs three-state scoring. Deployed on Replit.

- **V1 (done):** Layer 7 rule-based header analysis, weak config detection
- **V2 (in progress):** TLS/SSL validation via sslyze + Claude API contextual analysis with confidence scoring
- **V3 (roadmap):** Packet-level analysis, unified multi-layer scoring, PDF output

#### [Zero Trust API Gateway](https://github.com/Tanjot-Singh-cyber/gigcash-web-security)
FastAPI + Redis gateway implementing JWT auth, rate limiting, and zero-trust principles. In progress.

#### [PassVault](https://github.com/Tanjot-Singh-cyber/passvault)
Encrypted password manager in Python.

#### [File Integrity Scanner](https://github.com/Tanjot-Singh-cyber/file-integrity-scanner)
Hash-based file change detection tool.

---

### Methodology

- Source → sink → context before attempting any payload
- Map trust boundaries before exploitation
- Manual-first, tool-assisted second
- Document everything: hypothesis, test, result

PortSwigger labs completed: XSS (all 4 contexts), SQLi (including blind), CSRF, IDOR, access control, multi-step logic flaws, password reset poisoning, API authorization testing.

---

### Skills

**Offensive:** Burp Suite · OWASP Top 10 · GraphQL security · SSRF · IDOR · XSS · SQLi · API testing · Static code review (Semgrep)

**Development:** Python · FastAPI · Flask · Redis

**Certs:** Google Cybersecurity Professional Certificate · IBM Cybersecurity Analyst (in progress)

---

### Currently

- Hunting on HackerOne
- Building HeaderGuard V2
- Static code review for CVEs on open-source Python/JS repos

---

<p align="center">
  <a href="https://github.com/Tanjot-Singh-cyber/gigcash-web-security">AppSec portfolio & write-ups →</a>
</p>
