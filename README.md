# RaGenie Website

The informational website for RaGenie, an AI augmentation platform.

**Live site:** [ragenie.ai](https://ragenie.ai)

## What is this?

This repository contains the source for ragenie.ai—the website for RaGenie, an open source AI augmentation platform that combines multiple LLM providers with advanced Retrieval Augmented Generation.

## License

The website content and code are released under the MIT License.

## Deployment

This site is deployed on [Cloudflare Pages](https://pages.cloudflare.com/).

To deploy your own copy:

1. Fork this repository
2. Connect to Cloudflare Pages
3. Set build output directory to `/` (root)
4. No build command required—it's a static site

### Domain Setup

- Primary domain: ragenie.ai
- ragenie.com redirects to ragenie.ai (configured in Cloudflare DNS)

## Local Development

This is a static HTML/CSS site. No build process required.

```bash
# Serve locally (any static file server works)
python3 -m http.server 8000
# or
npx serve
```

Open http://localhost:8000

## Related Projects

- [RaGenie](https://github.com/rajivpant/ragenie) - The main application repository
- [Ragbot](https://github.com/rajivpant/ragbot) - Original AI assistant with CLI and Streamlit
- [ragbot-data](https://github.com/rajivpant/ragbot-data) - Shared data repository (private)
