<!-- HEADER -->
<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=2000&pause=1000&color=00FF00&center=true&vCenter=true&width=400&height=50&lines=%24+ssh+invaen" alt="header" />
</p>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=888888&center=true&vCenter=true&width=500&lines=Security+Researcher;Tool+Builder;Bug+Bounty+Hunter" alt="roles" />
</p>

---

### About

I build zero-dependency offensive security tools for bug bounty hunters.

```
I don't break into systems.
I break the assumptions developers made about them.
```

---

### Security Toolkit

A complete bug bounty workflow — from recon to report.

| Tool | Purpose |
|------|---------|
| **[ghost-recon](https://github.com/invaen/ghost-recon)** | Reconnaissance & fingerprinting |
| **[diff-hunter](https://github.com/invaen/diff-hunter)** | Attack surface monitoring |
| **[js-surgeon](https://github.com/invaen/js-surgeon)** | JavaScript static analysis |
| **[context-cannon](https://github.com/invaen/context-cannon)** | Adaptive payload generation |
| **[venom-cache](https://github.com/invaen/venom-cache)** | Web cache poisoning detection |
| **[ricochet](https://github.com/invaen/ricochet)** | Second-order vulnerability detection |

<details>
<summary><b>Workflow</b></summary>

<br>

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Recon     │────▶│   Analyze   │────▶│   Attack    │
└─────────────┘     └─────────────┘     └─────────────┘
  ghost-recon         js-surgeon         context-cannon
  diff-hunter                            venom-cache
                                         ricochet
```

**Recon** — `ghost-recon` discovers subdomains, probes live hosts, fingerprints tech. `diff-hunter` monitors for changes over time.

**Analyze** — `js-surgeon` extracts secrets, endpoints, and attack surface from JavaScript files.

**Attack** — `context-cannon` generates payloads that adapt to context. `venom-cache` finds cache poisoning. `ricochet` catches blind/stored vulns via callback correlation.

</details>

---

### Principles

```python
DEPENDENCIES = 0        # Pure stdlib. No supply chain risk.
BURP_REQUIRED = False   # CLI-first. Works anywhere.
OUTPUT_FORMAT = "json"  # Pipe to anything.
```

---

### Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,go,bash,linux,docker,git,vim&theme=dark" />
</p>

---

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=12&duration=4000&pause=2000&color=444444&center=true&vCenter=true&width=450&lines=Grinding+HTB+Academy+→+CWES+Certification" alt="status" />
</p>
