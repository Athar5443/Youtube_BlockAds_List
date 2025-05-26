<div align="center">
  <a href="https://github.com/Athar5443/Youtube_BlockAds_List/">
    <img src="https://img.shields.io/github/stars/your-username/yt-ads-blocklist?style=flat-square&logo=github" alt="Stars" />
  </a>
  <a href="https://github.com/Athar5443/Youtube_BlockAds_List/actions/workflows/publish.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/Athar5443/Youtube_BlockAds_List/ci.yml?style=flat-square&logo=github" alt="CI" />
  </a>
  <a href="https://github.com/Athar5443/Youtube_BlockAds_List/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/your-username/yt-ads-blocklist?style=flat-square&logo=open-source-initiative" alt="License" />
  </a>
  <a href="https://github.com/sponsors/your-username">
    <img src="https://img.shields.io/badge/Sponsor-&hearts;-pink?style=flat-square" alt="Sponsor" />
  </a>
</div>

---

## ✨ What Is This?

**YouTube Ads Blocklist** is a lightning-fast, auto-updating DNS blocklist that **eradicates** YouTube ads at the source.  
Integrate in **seconds** with Pi-hole, DNSMASQ, Unbound, AdBlockPlus, uBlock Origin, and more—no client-side extensions required.

---

## 🌟 Features

<div align="center">
  <table>
    <tr>
      <td align="center" width="120">🚫<br/>Ad-Blocking</td>
      <td align="center" width="120">⚡<br/>Performance-Tuned</td>
      <td align="center" width="120">🔄<br/>Auto-Updates</td>
      <td align="center" width="120">👀<br/>Transparent</td>
      <td align="center" width="120">📦<br/>Multi-Format</td>
    </tr>
  </table>
</div>

- **Ad-Blocking**: Stops YouTube ad domains before they load.  
- **Performance-Tuned**: Minimal list size for sub-millisecond DNS lookups.  
- **Auto-Updates**: CI pipeline rebuilds daily; your lists stay fresh with zero effort.  
- **Transparent**: Every domain in Git history—fully auditable.  
- **Multi-Format**: Pi-hole (IPv4/IPv6), DNSMASQ, Unbound, AdBlockPlus, plain-text.

---

## ⚡ Quick Start

```bash
# 1. Clone & Install
git clone https://github.com/your-username/yt-ads-blocklist.git
cd yt-ads-blocklist
npm ci

# 2. Build & Deploy
npm run build      # generate all formats
