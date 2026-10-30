# VidemakResearchAI

**The open‑source AI editor for academic writing.**  
Autocomplete that cites real papers, @‑cite from 250 M+ scholarly works, chat with your PDFs, a careful AI reviewer, and Word/LaTeX/PDF in and out. MIT licensed.

## Quick start
```bash
# Self‑host with Docker (requires Docker + Compose v2, ~4 GB RAM)
git clone https://github.com/noahotim/VidemakResearchAI.git
cd VidemakResearchAI
bash deploy/setup.sh      # writes .env with fresh secrets
docker compose up -d      # first build takes a few minutes
