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

<!-- ROW 1: RECON -->
<table align="center">
<tr>
<td width="50%">

### [ghost-recon](https://github.com/invaen/ghost-recon)
```
Reconnaissance that thinks about what it finds
```
Subdomain discovery, live host probing, tech fingerprinting, and intelligent analysis

`python` `zero-deps` `recon`

</td>
<td width="50%">

### [diff-hunter](https://github.com/invaen/diff-hunter)
```
Catch new attack surface before anyone else
```
Continuous monitoring for subdomain changes, endpoint exposure, and configuration drift

`python` `zero-deps` `monitoring`

</td>
</tr>

<!-- ROW 2: ANALYSIS -->
<tr>
<td width="50%">

### [js-surgeon](https://github.com/invaen/js-surgeon)
```
Extract secrets from JavaScript
```
Static analysis for bug bounty hunters — finds endpoints, API keys, and anti-patterns

`python` `zero-deps` `analysis`

</td>
<td width="50%">

### [context-cannon](https://github.com/invaen/context-cannon)
```
Payloads that adapt to context and filters
```
XSS, SQLi, SSTI, SSRF, LFI — encoded and filtered for your exact injection point

`python` `zero-deps` `payloads`

</td>
</tr>

<!-- ROW 3: ATTACK -->
<tr>
<td width="50%">

### [venom-cache](https://github.com/invaen/venom-cache)
```
Web cache poisoning from the command line
```
Finds unkeyed inputs that affect cached responses. No Burp Suite required.

`python` `zero-deps` `cache-poisoning`

</td>
<td width="50%">

### [ricochet](https://github.com/invaen/ricochet)
```
Second-order vulnerability detection
```
Detects blind XSS, stored XSS, second-order SQLi, SSTI through callback correlation

`python` `zero-deps` `oob-detection`

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
