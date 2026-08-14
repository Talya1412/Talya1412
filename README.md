<div align="center">

# Talya1412

Building dev tools that make supply chains less fragile.

</div>

---

## 🔭 What I build

**[mcpdoctor](https://github.com/Talya1412/mcpdoctor)** — the `npm audit` for your MCP server stack. One command finds the dead, stale, zombie and insecure servers wired into your agent configs, pins your versions, and monitors uptime.

```sh
npx mcpdoctor-audit
```

```text
name           verdict   version   reason
filesystem     OK        1.2.3     healthy
github         STALE     0.5.0     last publish 142 days ago
legacy-tool    ZOMBIE    0.1.0     no publish in 400 days
deprecated-x   INSECURE  1.0.0     CVE-2025-XXXXX: known vulnerability
ghost-server   MISSING   -         package not found on npm
remote-api     UNREACHABLE -        HTTP 502
```

## 📌 Pinned

- [mcpdoctor](https://github.com/Talya1412/mcpdoctor) · npm audit for MCP servers · TypeScript

## Stack

`TypeScript` · `Node.js` · CLI tooling · MCP ecosystem

---

<div align="center">
<i>MCP servers are the new supply chain — 52% are dead, 75% ship a known-CVE dep. Someone has to check.</i>
</div>