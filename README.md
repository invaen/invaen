```
  ██▓ ███▄    █ ██▒   █▓ ▄▄▄      ▓█████  ███▄    █
 ▓██▒ ██ ▀█   █▓██░   █▒▒████▄    ▓█   ▀  ██ ▀█   █
 ▒██▒▓██  ▀█ ██▒▓██  █▒░▒██  ▀█▄  ▒███   ▓██  ▀█ ██▒
 ░██░▓██▒  ▐▌██▒ ▒██ █░░░██▄▄▄▄██ ▒▓█  ▄ ▓██▒  ▐▌██▒
 ░██░▒██░   ▓██░  ▒▀█░   ▓█   ▓██▒░▒████▒▒██░   ▓██░
 ░▓  ░ ▒░   ▒ ▒   ░ ▐░   ▒▒   ▓▒█░░░ ▒░ ░░ ▒░   ▒ ▒
  ▒ ░░ ░░   ░ ▒░  ░ ░░    ▒   ▒▒ ░ ░ ░  ░░ ░░   ░ ▒░
  ▒ ░   ░   ░ ░     ░░    ░   ▒      ░      ░   ░ ░
  ░           ░      ░        ░  ░   ░  ░         ░
                    ░
```

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&repeat=false&width=600&lines=%24+whoami" alt="whoami" />
</p>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&duration=2000&pause=500&color=888888&center=true&vCenter=true&width=700&lines=Security+Researcher+%7C+Tool+Builder+%7C+HTB+Academy;I+don't+break+systems.+I+break+assumptions." alt="tagline" />
</p>

<br>

<h2 align="center">
「  T O O L K I T  」
</h2>

<p align="center">
<sub>Zero-dependency offensive security tools for bug bounty hunters</sub>
</p>

<br>

<table align="center">
<tr>
<td align="center" colspan="2">
<br>
<img src="https://img.shields.io/badge/▸_RECONNAISSANCE-1a1a2e?style=for-the-badge" />
</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/ghost-recon">👻 ghost-recon</a></h3>

> *Reconnaissance that thinks about what it finds*

Subdomain discovery, live host probing, tech fingerprinting, and intelligent analysis

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/diff-hunter">🎯 diff-hunter</a></h3>

> *Catch new attack surface before anyone else*

Continuous monitoring for subdomain changes, endpoint exposure, and configuration drift

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
</tr>
<tr>
<td align="center" colspan="2">
<br>
<img src="https://img.shields.io/badge/▸_ANALYSIS-1a1a2e?style=for-the-badge" />
</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/js-surgeon">🔪 js-surgeon</a></h3>

> *Extract secrets from JavaScript*

Static analysis for bug bounty hunters — finds endpoints, API keys, and anti-patterns

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/context-cannon">💣 context-cannon</a></h3>

> *Payloads that adapt to context and filters*

XSS, SQLi, SSTI, SSRF, LFI — encoded and filtered for your exact injection point

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
</tr>
<tr>
<td align="center" colspan="2">
<br>
<img src="https://img.shields.io/badge/▸_EXPLOITATION-1a1a2e?style=for-the-badge" />
</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/venom-cache">🧪 venom-cache</a></h3>

> *Web cache poisoning from the command line*

Finds unkeyed inputs that affect cached responses. No Burp Suite required.

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/invaen/ricochet">📡 ricochet</a></h3>

> *Second-order vulnerability detection*

Detects blind XSS, stored XSS, second-order SQLi, SSTI through callback correlation

<img src="https://img.shields.io/badge/python-306998?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/zero--deps-00ff00?style=flat-square" />

</td>
</tr>
</table>

<br>

<h2 align="center">
「  W O R K F L O W  」
</h2>

```
  ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
  │              │      │              │      │              │
  │    RECON     │─────▶│   ANALYZE    │─────▶│    ATTACK    │
  │              │      │              │      │              │
  └──────────────┘      └──────────────┘      └──────────────┘
        │                     │                     │
        ▼                     ▼                     ▼
   ghost-recon           js-surgeon           context-cannon
   diff-hunter                                 venom-cache
                                                ricochet
```

<br>

<h2 align="center">
「  P H I L O S O P H Y  」
</h2>

```python
DEPENDENCIES  = 0        # Pure stdlib. No supply chain risk.
BURP_REQUIRED = False    # CLI-first. Works anywhere.
OUTPUT        = "json"   # Pipe to anything.
```

<br>

---

<p align="center">
<img src="https://skillicons.dev/icons?i=python,go,bash,linux,vim&theme=dark" />
</p>

<p align="center">
<sub>Currently grinding HTB Academy</sub>
</p>
