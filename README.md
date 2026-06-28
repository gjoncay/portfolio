# Portfolio

Welcome to my portfolio! Here you can find highlights of the projects I've worked on.

---

## Projects

### 🛡️ Chinook Cyber Ecosystem

**[Chinook Cyber Homepage](https://github.com/gjoncay/chinookcyber_homepage)**
*A modern, minimalist splash page acting as a portal to the Chinook Cyber ecosystem.*
**Tech Stack:** Next.js 16, Tailwind CSS 4, Lucide Icons
**Description:** A dark-mode first design system portal linking to the Cyber Planner and Threat Group Browser, keeping visual consistency through custom glassmorphism utilities.

**[CyberSandBox (Cyber Planner)](https://github.com/gjoncay/cyber-planning-web-app)**
*An OAKOC-based Cyber Threat Intelligence planning and modeling surface.*
**Tech Stack:** Next.js 15, React 19, Tailwind CSS, React Flow, Zustand
**Description:** Applies US Army intelligence-preparation-of-the-battlefield concepts (OAKOC/IPOE) to cyber defense. Analysts map networks as defended terrain, enriched with live vulnerability data (CISA KEV, FIRST EPSS), and present dual-lens (Tactical/Strategic) threat briefings.

**[MITRE Diamond Dashboard (ATT&CK Browser)](https://github.com/gjoncay/chinook-cti)**
*A threat-actor intelligence browser built around the Diamond Model of Intrusion Analysis.*
**Tech Stack:** React 18, Vite, TypeScript, Tailwind CSS, Recharts, Zustand
**Description:** Sourced from MITRE ATT&CK and enriched with MITRE D3FEND defensive coverage. Features a threat-landscape dashboard, Diamond Model mapping for every actor, tactic phase profiles, and defensive coverage tracking.

### 📊 Network & Traffic Analysis

**[MikroTik ELK Stack](https://github.com/gjoncay/ELK-homelan)**
*A comprehensive home-LAN traffic analysis stack running in Docker.*
**Tech Stack:** Elasticsearch, Kibana, Fleet Server, Zeek, Tailscale
**Description:** Ingests IPFIX and TZSP packet capture streams from a MikroTik router. Processes data, performs dynamic IP-to-domain and friendly-name enrichments using Zeek, and presents insights via prebuilt Kibana dashboards, all accessible securely via a Tailscale sidecar.

**[Netflow Data Dashboard](https://github.com/gjoncay/IPFIX_Dashboard)**
*Interactive network-traffic dashboard for NetFlow/IPFIX records.*
**Tech Stack:** Python, Streamlit, DuckDB, Pandas, Plotly
**Description:** Parses `nfcapd` captures into a fast columnar store, enriches external IPs with GeoIP/ASN/threat-intel data, and surfaces analytics including top talkers, per-device profiles, beacon detection, and a persistent watchlist.

### 💻 Web Applications

**[Sophie Counseling Site](https://github.com/gjoncay/sophie-counseling-site)**
*A modern, calming web presence for a licensed mental health counselor.*
**Tech Stack:** React, Vanilla CSS, Vite
**Description:** A responsive, performant, and beautifully designed website for a mental health practice. Features a calming color palette, smooth micro-animations, and SEO/Open Graph optimization to ensure a welcoming experience for prospective clients.

**[Seattle Move App](https://github.com/gjoncay/seattle-move-app)**
*Custom relocation planner and dashboard to manage a PCS move.*
**Tech Stack:** Next.js, Tailwind CSS, Leaflet Maps, Supabase
**Description:** Features interactive countdowns, phase-based checklists, an interactive neighborhood/transit map, and a scrapbook to organize housing options and freeform notes.

**[Kanban To-Do](https://github.com/gjoncay/kanban-todo)**
*Small, dependency-free shared Kanban board.*
**Tech Stack:** Node.js, HTML/JS/CSS, LocalStorage
**Description:** A single static page talking to a tiny Node server that persists tasks to a JSON file. Features drag-and-drop, editable categories, offline caching, and is designed to run securely behind a Tailscale sidecar.

**[Cycling Dashboard](https://github.com/gjoncay/cycling-dashboard)**
*Self-hosted dashboard for Strava cycling data.*
**Tech Stack:** FastAPI, SQLite, Jinja2, Leaflet, Chart.js
**Description:** Visualizes high-density cycling stats with a dark route heatmap featuring glowing paths (green for road, tan for trail). Includes a per-ride mechanical and qualitative markdown journal linked to Strava activities.

### 🛠️ Developer Tools & Research

**App Template**
*Docker web app boilerplate.*
**Tech Stack:** Docker, Tailscale
**Description:** A copy-paste template to quickly start new Docker web apps accessible securely via Tailscale sidecars (`https://<app>.tailnet.ts.net`) using automatic Let's Encrypt certificates.

**Threat Horizon PRC Masterclass**
*Threat intelligence research.*
**Description:** A collection of scripts, text-to-speech processing pipelines, and markdown notes analyzing the PRC threat landscape based on advanced threat intelligence.

---

**Screenshots:**
*(Add your screenshots here in the `assets` folder and link them below!)*

<!-- Example screenshot link once you upload an image:
![Sophie Site Homepage](assets/homepage.png)
-->
