# Codewars Community Tools (Meta-Repo)

This repository is a **single landing page + catalog** for a set of unofficial, community-built tools that extend, augment, and experiment with the Codewars platform.

If you found one tool and are wondering "what else exists?", start here.

## Tool Catalog

- **Polyglot** - a userscript with optional UI/QoL improvements.
  - Repo: [hobovsky/polyglot](https://github.com/hobovsky/polyglot)
  - Tech stack: Tampermonkey userscript, JavaScript, jQuery
  - Install: [script](https://github.com/hobovsky/polyglot/releases/latest/download/polyglot.js)
- **`cw-lsp`** - IDE-like completion/diagnostics in the editor
  - Repo: [hobovsky/cw-lsp](https://github.com/hobovsky/cw-lsp)
  - Tech stack:
    - Frontend: Tampermonkey userscript, JavaScript, jQuery
    - Backend: TypeScript, Express.js, LSP API
  - Install: [script](https://github.com/hobovsky/cw-lsp/raw/refs/heads/main/client/cw-lsp.user.js)
- **Codot** - AI (and not only) assistant in the UI
  - Repo: [`codot-client`](https://github.com/hobovsky/codot-client) for user frontend. Backend repo is not public at the moment, but it's open to collaboration.
  - Tech stack:
    - Frontend: Tampermonkey userscript, JavaScript, jQuery
    - Backend: JavaScript, Express.js, OpenAI
  - Install: frontend [script](https://github.com/hobovsky/codot-client/raw/main/src/codot.user.js)
- **Katafix** - a web app with AI-powered tools for content maintenance
  - Deployment: [Katafix](https://katafix.fly.dev)
  - Tech stack:
    - Frontend: TypeScript, React
    - Backend: Ruby on Rails, OpenAI
  - Docs: [How to use Katafix to translate Codewars kata](https://docs.google.com/document/d/e/2PACX-1vSUscW-BMybu0ocuwyHN8VDdSIngk2Bno7tziIhsDn6w5-fgIygbEsaLlqTEs-7jJyCiMcWWA80Zet2/pub), [How to use Katafix to update JavaScript kata to Node 18](https://docs.google.com/document/d/e/2PACX-1vSpDFTJsZvmv_ov6akL-CbIKRrP05DvbGEJYZ2ZxCnL274S16hi9norw4NMQP20EIFqgcQMY2oNB0jB/pub)
  - Repo is not public at the moment, but it's open to collaboration.
- **Katasniplib** - a userscript with in-editor snippet library
  - Repo: [hobovsky/katasniplib](https://github.com/hobovsky/katasniplib)
  - Tech stack: Tampermonkey userscript, JavaScript, jQuery
  - Install: [script](https://github.com/hobovsky/katasniplib/raw/main/src/katasniplib.user.js)
- **`cw-python-tests-updater`** - a userscript with Python test migration shortcuts
  - Repo: [hobovsky/cw-python-tests-updater](https://github.com/hobovsky/cw-python-tests-updater)
  - Tech stack: Tampermonkey userscript, JavaScript, jQuery
  - Install: [script](https://github.com/hobovsky/cw-python-tests-updater/raw/refs/heads/main/decorator_script.user.js)
- **Authoring Examples** - a kata collection of "what good looks like" across languages
  - Tech stack: Codewars collections
  - Link: [Authoring examples](https://www.codewars.com/collections/authoring-examples)
- **Cody** - a Discord bot with feeds and early quality signals  
  - Repo is not public at the moment, but it's open to collaboration.
  - Tech stack: TypeScript, discord.js, OpenAI
- **`cw-faq`** - a wiki with frequently-given answers library
  - Repo: [hobovsky/cw-faq](https://github.com/hobovsky/cw-faq)
  - Tech stack: Markdown, Github wiki
  - FAQ: [wiki](https://github.com/hobovsky/cw-faq/wiki/Frequently-Given-Answers)

## Contributing to tools

Contributions are generally welcome across the tool ecosystem.

- You can **report bugs**, **suggest features**, or **submit pull requests** with fixes and improvements.
- For **new features / larger changes**, please open an issue (or start a discussion) first so we can align on scope and avoid wasted effort.
- I'm easiest to reach via a ping on the [**Codewars Discord**](https://discord.gg/mSwJWRvkHA).
- Some tool repos are **not public**. This doesn’t mean they’re closed - usually the codebase just isn't prepared for broad drive-by contributions yet. If you want to collaborate, contact me on Discord and we'll figure out the best way.
- Please use **responsible disclosure** for security/privacy issues: contact me privately first (Discord) instead of opening a public issue.

<!--
### Analytics / Local Workflow

- **Codewars Analyze** - activity heatmap + richer profile view (web app)  
  Docs: `tools/codewars-analyze.md` • Repo: `<REPO_URL>` • Deployment: `<DEPLOYMENT_URL>`
- **Local Kata CLI** - local workflow + runner integration (CLI)  
  Docs: `tools/local-kata-cli.md` • Repo: `<REPO_URL>` • Releases: `<RELEASES_URL>`
- **JetBrains / IntelliJ Plugin** - train/submit from IDE (plugin)  
  Docs: `tools/jetbrains-plugin.md` • Repo: `<REPO_URL>` • Marketplace: `<MARKETPLACE_URL>`

## Proposals / Experiments

These are design docs / prototypes, not necessarily active projects.

- `proposals/kata-index.md` - semantic kata index for discovery/learning/maintenance
- `proposals/katagent.md` - connecting tools into an "agentic maintenance pipeline"
- `proposals/poster-assistant.md` - assisted posting for Discussions
- `proposals/challenge-formats.md` - timed / limited-attempt formats (paused)



## Contributing to this meta-repo

See `CONTRIBUTING.md`.

## License

`<LICENSE_PLACEHOLDER>`

-->
