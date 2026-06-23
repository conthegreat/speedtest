# speedtest.networkcontractor.co.uk

**Throughput Test Endpoints** for ThousandEyes agents and routers.

Clean direct download URLs:
- `https://speedtest.networkcontractor.co.uk/10mb`
- `https://speedtest.networkcontractor.co.uk/100mb`
- `https://speedtest.networkcontractor.co.uk/1gb`

## Setup (for conthegreat)

1. Upload `index.html` to your GitHub repository
2. Enable GitHub Pages + connect custom domain `speedtest.networkcontractor.co.uk`
3. Create three files in the root of the repo:
   - `10mb` (10 MB binary)
   - `100mb` (100 MB binary)
   - `1gb` (1 GB binary)
4. Push — the clean URLs above will work immediately

For large files, you can use **Git LFS**.

## How to use in ThousandEyes

Copy any of the three URLs above into an **HTTP Server** test.  
Add `?nocache=1735123456789` to bust cache on repeated runs.

## Files

- `index.html` — The website (hosted on GitHub Pages)
- `README.md` — This file

---

Hosted on GitHub Pages • Custom domain: speedtest.networkcontractor.co.uk

Not affiliated with ThousandEyes.