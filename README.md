
raw
Website readme · MD
# Website
 
The public-facing Sunrise Atelier website — program information, volunteer interest form, and the organization's front door.
 
---
 
## Tech stack
 
- **Frontend** — React, TypeScript, Tailwind CSS
- **Database** — Supabase (volunteer form submissions)
## Getting started
 
### Prerequisites
 
- Node.js 18+
- Supabase account or local instance
### Install
 
```bash
git clone https://github.com/sunrise-atelier/website
cd website
npm install
```
 
### Environment variables
 
```bash
cp .env.example .env.local
# fill in your Supabase URL and anon key
```
 
### Run locally
 
```bash
npm run dev
```
 
Open [http://localhost:3000](http://localhost:3000).
 
## Contributing
 
See [CONTRIBUTING.md](https://github.com/sunrise-atelier/sunrise-api/blob/main/CONTRIBUTING.md) for guidelines. Design and copy contributions are as welcome as code. Browse [`good first issue`](../../issues?q=is%3Aopen+label%3A%22good+first+issue%22) to start.
 
---
 
Part of [Sunrise Atelier](https://github.com/sunrise-atelier) — free, open-source tools for underserved communities.
