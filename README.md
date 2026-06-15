<!--
  GitHub Profile README for Ali Firas / thesmartshadow
  Place this file inside: https://github.com/thesmartshadow/thesmartshadow
-->

<div align="center">

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2600&pause=700&color=36BCF7&center=true&vCenter=true&width=900&lines=Ali+Firas+%7C+thesmartshadow;Open+Source+Security+Researcher;Deep+Source-Code+Audits;CVE+%2F+GHSA+Research;Reading+bugs+before+they+speak" alt="Typing SVG" />

  <br />

  <a href="https://github.com/thesmartshadow">
    <img src="https://img.shields.io/badge/GitHub-thesmartshadow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://hackerone.com/thesmartshadow">
    <img src="https://img.shields.io/badge/HackerOne-thesmartshadow-494649?style=for-the-badge&logo=hackerone&logoColor=white" alt="HackerOne" />
  </a>
  <a href="https://www.linkedin.com/in/ali-shmery/">
    <img src="https://img.shields.io/badge/LinkedIn-Ali%20Firas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:alishmery18@gmail.com">
    <img src="https://img.shields.io/badge/Email-Responsible%20Disclosure-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

  <br />
  <br />

  <img src="https://komarev.com/ghpvc/?username=thesmartshadow&style=flat-square&color=36BCF7" alt="Profile views" />
  <img src="https://img.shields.io/badge/Focus-OSS%20Security-0d1117?style=flat-square" alt="OSS Security" />
  <img src="https://img.shields.io/badge/Research-CVE%20%2F%20GHSA-0d1117?style=flat-square" alt="CVE GHSA" />
  <img src="https://img.shields.io/badge/Mode-Responsible%20Disclosure-0d1117?style=flat-square" alt="Responsible Disclosure" />

</div>

---

## About Me

I am **Ali Firas**, also known as **thesmartshadow** — an independent security researcher focused on **open-source security**, **deep source-code review**, and **real vulnerability validation**.

My work is centered around finding implementation-level security flaws in real projects, reducing weak reports into strong evidence, and turning complex behavior into clear, reproducible vulnerability reports.

I care about the part most people skip:

> reading the code path until the bug stops hiding.

---

## Research Identity

```js
const thesmartshadow = {
  name: "Ali Firas",
  handle: "thesmartshadow",
  role: "Open Source Security Researcher",
  country: "Iraq",

  focus: [
    "Deep source-code security review",
    "CVE / GHSA vulnerability research",
    "Access control and authorization flaws",
    "Parser, protocol, and runtime edge cases",
    "Memory-safety and denial-of-service analysis",
    "Responsible disclosure and remediation-focused reporting"
  ],

  ecosystems: {
    languages: ["C", "C++", "Rust", "Go", "Ruby", "JavaScript", "Python", "Bash"],
    platforms: ["Linux", "GitHub", "Docker", "Node.js", "RubyGems", "npm", "Go modules"],
    security: ["CodeQL", "Semgrep", "Burp Suite", "Ghidra", "GDB", "Nuclei", "Wireshark"]
  },

  method: [
    "Read documentation first",
    "Map the trust boundary",
    "Trace the real code flow",
    "Build a minimal reproducible PoC",
    "Compare expected vs actual behavior",
    "Suggest a practical fix"
  ],

  motto: "Logic + Monster = Zero-day"
};
````

---

## What I Work On

<table>
  <tr>
    <td width="50%">
      <h3>Source-Code Security Review</h3>
      <p>
        I review open-source projects by tracing real execution paths, permission boundaries,
        parser states, protocol assumptions, and unsafe edge cases.
      </p>
    </td>
    <td width="50%">
      <h3>CVE / GHSA Research</h3>
      <p>
        I focus on reports that can survive maintainer review: clear impact, affected versions,
        root cause, practical exploit scenario, and reproducible evidence.
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>Bug Bounty & VDP</h3>
      <p>
        I work on responsible disclosure through security programs, GitHub Security Advisories,
        CVE processes, and coordinated vulnerability reports.
      </p>
    </td>
    <td width="50%">
      <h3>Patch-Oriented Reporting</h3>
      <p>
        I prefer reports that do not stop at “this is broken”, but explain why it happened,
        where the trust boundary failed, and how to fix it safely.
      </p>
    </td>
  </tr>
</table>

---

## Selected Public Security Work

| Area                             |           Record | Project / Ecosystem         | Core Issue                                             |
| -------------------------------- | ---------------: | --------------------------- | ------------------------------------------------------ |
| Open-source security             | `CVE-2026-32808` | pyLoad                      | Path traversal leading to arbitrary file deletion      |
| Linux / eBPF ecosystem           | `CVE-2026-10722` | cilium/ebpf                 | Invalid BTF/BTF.ext parsing leading to panic           |
| Ruby ecosystem                   | `CVE-2026-25500` | Rack                        | Stored XSS through unsafe directory rendering behavior |
| Microsoft ecosystem              | `CVE-2026-45539` | Microsoft / GitHub Advisory | Security issue reported through coordinated disclosure |
| Ruby runtime / package ecosystem | `CVE-2026-37731` | Ruby json                   | Denial-of-service class issue                          |
| Rust / crypto bindings           | `CVE-2026-45784` | rust-openssl                | Security issue in OpenSSL Rust ecosystem               |
| Node.js / npm ecosystem          | `CVE-2026-44724` | systeminformation           | Security issue in npm package behavior                 |
| Markdown / OSS package           | `CVE-2025-59717` | DigitalOcean do-markdownit  | Markdown rendering security issue                      |
| Rust CLI ecosystem               | `CVE-2025-67124` | miniserve                   | Open-source vulnerability research                     |
| C++ CLI ecosystem                | `CVE-2025-67125` | docopt.cpp                  | Open-source vulnerability research                     |

> I keep my reports focused on reproducibility, real impact, and maintainable fixes.

---

## Research Focus Map

```text
Authorization bugs        ████████████████████  High focus
OSS package security      ████████████████████  High focus
Parser edge cases         ██████████████████░░  Strong focus
Protocol logic flaws      █████████████████░░░  Strong focus
Runtime boundaries        ████████████████░░░░  Active focus
Memory safety             ███████████████░░░░░  Active focus
Supply-chain behavior     ██████████████░░░░░░  Active focus
```

---

## Current Interests

* QUIC / HTTP/3 implementation behavior
* Linux, eBPF, and kernel-adjacent userland security
* Rust, Go, Ruby, Node.js, and C/C++ open-source ecosystems
* GitHub Security Advisory workflows
* CVE-quality vulnerability documentation
* AI-assisted security research with strict human validation

---

## Tools & Technologies

<div align="center">

  <img src="https://skillicons.dev/icons?i=linux,bash,c,cpp,rust,go,python,js,nodejs,ruby,git,github,docker,vscode" alt="Skills" />

</div>

<br />

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>C, C++, Rust, Go, Ruby, JavaScript, Python, Bash</td>
  </tr>
  <tr>
    <td><b>Security Review</b></td>
    <td>Manual source-code review, threat modeling, PoC validation, patch review</td>
  </tr>
  <tr>
    <td><b>Research Tools</b></td>
    <td>Burp Suite, Semgrep, CodeQL, Ghidra, GDB, Nuclei, Wireshark</td>
  </tr>
  <tr>
    <td><b>Infrastructure</b></td>
    <td>Linux, Docker, GitHub Actions, local harnesses, reproducible test environments</td>
  </tr>
</table>

---

## How I Approach a Vulnerability

```text
1. Understand the project and its documented security model
2. Identify trust boundaries and attacker-controlled inputs
3. Trace the full code path instead of guessing from symptoms
4. Build a minimal PoC that proves the behavior in practice
5. Validate affected and fixed versions when possible
6. Explain root cause, impact, exploit scenario, and remediation
7. Report responsibly with enough detail for maintainers to act
```

---

## GitHub Activity

<div align="center">

  <img height="170" src="https://github-readme-stats.vercel.app/api?username=thesmartshadow&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&count_private=false" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thesmartshadow&layout=compact&theme=transparent&hide_border=true" alt="Top Languages" />

</div>

<div align="center">

  <img src="https://streak-stats.demolab.com?user=thesmartshadow&theme=transparent&hide_border=true" alt="GitHub Streak" />

</div>

<div align="center">

  <img src="https://github-profile-trophy.vercel.app/?username=thesmartshadow&theme=darkhub&no-frame=true&no-bg=true&margin-w=8" alt="GitHub Trophies" />

</div>

---

## Connect

<div align="center">

  <a href="https://github.com/thesmartshadow">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://hackerone.com/thesmartshadow">
    <img src="https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white" alt="HackerOne" />
  </a>
  <a href="https://www.linkedin.com/in/ali-shmery/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:alishmery18@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

</div>

---

<div align="center">

<b>Security research is not about noise.</b> <br />
It is about proving the exact point where trust breaks.

</div>

