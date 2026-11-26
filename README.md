# ETF Guide LK

A public, beginner-friendly ETF guide written from Sri Lanka. Live site: https://kusal-tharindu.github.io/invest-guide/

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and published with GitHub Pages.

## Run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Open http://127.0.0.1:8000.

## Add content

1. Add a Markdown file under the right folder in `docs/`.
2. Add it to `nav` in `mkdocs.yml`.
3. Push to `main`. GitHub Actions builds and deploys the site.

## First-time GitHub setup

In the repo, go to Settings, then Pages, and set Source to **GitHub Actions**.

## Disclaimer

For educational purposes only. This is a personal learning journal, not financial, investment, tax, or legal advice. Company, fund, and index names are trademarks of their respective owners and are used for identification only. No affiliation or endorsement is implied.

## License

© 2026 Kusal Tharindu (Oxelan). All rights reserved. See [LICENSE](LICENSE).
