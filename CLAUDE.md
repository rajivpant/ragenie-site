# Claude Code Context: ragenie-site

## Repository: ragenie-site (PUBLIC)

This is a **PUBLIC** repository containing the informational website for RaGenie.

## Repository Ecosystem

| Repository | Type | Purpose | Location |
|------------|------|---------|----------|
| **ragbot** | Public | AI assistant CLI and Streamlit UI | `~/projects/my-projects/ragbot/` |
| **ragbot-site** | Public | Website for ragbot.ai | `~/projects/my-projects/ragbot-site/` |
| **ragenie** | Public | Next-gen RAG platform | `~/projects/my-projects/ragenie/` |
| **ragenie-site** | Public | Website for ragenie.ai | `~/projects/my-projects/ragenie-site/` |
| **ragbot-data** | Private | Shared data for both products | `~/ragbot-data/` |
| **synthesis-coding-site** | Public | Website for synthesiscoding.com | `~/projects/my-projects/synthesis-coding-site/` |

Note: Home directory varies by machine (`/Users/rajiv` vs `/Users/rajivpant`), so use `~` for paths.

## VS Code Workspace

All repositories are in the same VS Code workspace for unified development.

## Site Purpose

- Informational website for RaGenie at ragenie.ai
- ragenie.com redirects to ragenie.ai (configured in Cloudflare)
- Simple, non-commercial presentation of the open source product
- Static HTML/CSS site deployed on Cloudflare Pages

## Site Structure

```text
ragenie-site/
├── index.html        # Main page
├── 404.html          # Error page
├── _headers          # Cloudflare security headers
├── _redirects        # www redirect rules
├── robots.txt        # Search engine instructions
├── llms.txt          # AI-friendly site description
├── favicon.svg       # Site icon (genie lamp)
├── README.md         # Repository documentation
└── CLAUDE.md         # This file
```

## Design Guidelines

- Clean, minimal design matching synthesiscoding.com style
- Newsreader + JetBrains Mono fonts
- Non-commercial, informational tone
- Subtle author attribution in footer
- Links to GitHub repo and related projects

## Deployment

- Hosted on Cloudflare Pages
- Connected to GitHub for automatic deployments
- No build step required (static site)
- ragenie.com → ragenie.ai redirect configured in Cloudflare DNS

## Git Operations

**IMPORTANT**: Before any git commands for this repo, ensure you are in the correct directory:

```bash
cd ~/projects/my-projects/ragenie-site
```

Each repo in the ecosystem has its own git history.
