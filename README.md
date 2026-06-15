<img src="https://capsule-render.vercel.app/api?type=waving&color=0d0d0d&height=200&section=header&text=Tanjot%20Singh&fontSize=50&fontColor=00FF41&fontAlignY=35&desc=Application%20Security%20Researcher&descColor=00FF41&descAlignY=55&descSize=20&animation=fadeIn" width="100%"/>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Tanjot+Singh;Application+Security+Researcher;CVE+Author+%7C+Bug+Bounty+Hunter;B.Tech+CSE+%40+MIET+Jammu+%2728" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://linkedin.com/in/tanjot-singh-69579a352">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Tanjot-Singh-cyber/gigcash-web-security">
    <img src="https://img.shields.io/badge/AppSec_Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### About Me

```python
tanjot = {
    "focus"      : "Application Security",
    "degree"     : "B.Tech CSE @ MIET Jammu '28",
    "approach"   : "Manual-first. Proof-of-work over certifications.",
    "hunting"    : ["HackerOne", "Bugbase", "GitHub OSS CVEs"],
    "currently"  : ["HeaderGuard V2 deployed", "Open-source security audits", "CVE hunting"],
}
```

---

### Security Findings

| # | Vulnerability | Target | Severity | Reference |
|---|--------------|--------|----------|-----------|
| 1 | **SSRF** — unvalidated URL parameter allows internal network requests | Blombooru (FastAPI) | ![High](https://img.shields.io/badge/High-FF0000?style=flat-square) | GHSA-5c5w-x8jp-fjqw · CWE-918 · Fix planned v1.40.0 · CVE in progress |
| 2 | **SSRF bypass** — `validate_url()` absent on feed edit path, bypassing developer's own protection | newspipe (Flask) | ![Medium](https://img.shields.io/badge/Medium-FFA500?style=flat-square) | CWE-918 · Disclosed via email |
| 3 | **Unauthenticated SSRF** — no-auth default + unvalidated destination parameter | mediaflow-proxy (FastAPI) | ![Medium](https://img.shields.io/badge/Medium-FFA500?style=flat-square) | CWE-918 · Disclosed via email |
| 4 | **IDOR/BOLA** — GraphQL query accepts cross-user UUIDs without authorization check | subspace.money | ![High](https://img.shields.io/badge/High-FF0000?style=flat-square) | CWE-639 · Reported via Bugbase |

---

### Skills & Tools

**Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-4B2B8B?style=for-the-badge&logo=semgrep&logoColor=white)
![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white)

**Development**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Tools**

![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### Projects

<table>
  <tr>
    <td width="50%">
      <h3>HeaderGuard</h3>
      <p>Three-layer web security analyzer — HTTP header inspection, TLS/SSL validation, and Gemini AI contextual analysis. Weighted grading, never outputs "Safe", graceful degradation.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/Status-V2_Complete-4CAF50?style=flat-square" />
    </td>
    <td width="50%">
      <h3>PassVault</h3>
      <p>Encrypted CLI password manager. Fernet/AES encryption, SHA-256 + salt master password hashing, cryptographically secure generation via secrets module.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Status-Complete-4CAF50?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>File Integrity Scanner</h3>
      <p>Static USB malware scanner. Magic byte detection, SHA-256 integrity verification, ECDSA-signed forensic reports for tamper-evident output.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Status-Complete-4CAF50?style=flat-square" />
    </td>
    <td width="50%">
      <h3>Zero Trust API Gateway</h3>
      <p>FastAPI + Redis gateway with JWT auth, rate limiting, and AI log analysis. Planned next after HeaderGuard V3.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Status-Planned-808080?style=flat-square" />
    </td>
  </tr>
</table>

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tanjot-Singh-cyber&theme=radical&hide_border=true" />
</p>

---

### Currently

- Open-source security audits — static code review via Semgrep + manual source tracing
- CVE hunting on actively maintained Python/JS repos (500–3000 stars)
- blombooru SSRF advisory accepted — fix incoming, CVE in progress
- Building HeaderGuard V3 — packet capture + unified scoring

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Tanjot-Singh-cyber&color=00FF41&style=flat-square&label=Profile+Views" />
</p>

<p align="center">
  <a href="https://github.com/Tanjot-Singh-cyber/gigcash-web-security">
    <img src="https://img.shields.io/badge/→_AppSec_Portfolio_%26_Write--ups-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=Always+learning.;Breaking+things+legally.;Manual-first.+Tools-assisted.;Open+to+internships+%2726.;If+it+has+an+API%2C+I+will+test+it." alt="Typing SVG" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d0d0d&height=120&section=footer" width="100%"/>
