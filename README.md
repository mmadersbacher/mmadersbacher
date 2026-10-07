<img src="banner.svg" alt="Mario Madersbacher — Security & Networking, Austria" width="100%">

# Mario Madersbacher

Security & networking, Austria. I build small tools to understand how systems actually behave — network scanners, device fingerprinting, and the occasional thing that pokes at software from the outside. When I can't explain a behavior, I end up writing the tool that shows me.

Rust and Go when it has to be fast, Python when I just want the answer. Linux as a daily driver.

## Published CVEs

**`CVE-2026-103043`** — regular-expression denial of service in **anchorme**'s IPv6 host-extraction regex (≤ 3.0.8). A crafted URL of under 100 bytes makes the regex backtrack exponentially and blocks the Node.js event loop; no fixed release as of October 2026.
<sub>High · CVSS 7.5 (v3.1) / 8.7 (v4) · CWE-1333 · [VulnCheck advisory](https://www.vulncheck.com/advisories/anchorme-through-3.0.8-regular-expression-denial-of-service) · [CVE record](https://www.cve.org/CVERecord?id=CVE-2026-103043) · credited Mario Madersbacher (finder)</sub>

**`CVE-2026-90776`** — quadratic-complexity denial of service in **nodemailer**'s `addressparser` (9.1.0–10.0.4). Crafted comment-joined addresses stall the Node.js event loop, reachable unauthenticated through mailparser on inbound mail. Fixed in v10.0.5.
<sub>High · CVSS 7.5 (v3.1) / 8.7 (v4) · CWE-407 · [GHSA-prgh-xp8r-p3m5](https://github.com/nodemailer/nodemailer/security/advisories/GHSA-prgh-xp8r-p3m5) · assigned by VulnCheck · credited `mmadersbacher`</sub>

**`CVE-2026-90492`** — OS command injection in **webgjc/web_robot** 2.8.0 (CWE-78): unsanitized request input reaches a shell call.
<sub>Medium · CVSS 6.3 (v3.1) / 5.3 (v4) · [VDB-403080](https://vuldb.com/?id.403080) · credited `Telqrrr` on VulDB</sub>

## Elsewhere

TryHackMe Junior Penetration Tester · a few CTF placements · accepted bug-bounty reports. Currently going deeper into network protocols, reverse engineering, and Rust.

<sub>[mmadersbacher.github.io](https://mmadersbacher.github.io) · [CTFtime](https://ctftime.org/user/264976)</sub>
