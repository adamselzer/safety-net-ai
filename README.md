# Safety-Net AI

The front door to a four-project portfolio on AI in the public-benefits safety net.
A single navigable hub that presents the thesis, the four projects (with consistent
labels and headline results), how they compose, the cross-cutting principles, and
the shared **Civil** design system.

This is the suite-level information architecture for the portfolio: one hub, one
vocabulary, links out to each project and the design system. It is a static page
(`index.html`) — open it directly, serve it locally, or host it on GitHub Pages.

## The projects

| Pattern | Repo |
|---|---|
| MCP | [rules-as-code-mcp](https://github.com/adamselzer/rules-as-code-mcp) |
| RAG | [policy-manual-rag](https://github.com/adamselzer/policy-manual-rag) |
| Agents | [benefits-intake-agent](https://github.com/adamselzer/benefits-intake-agent) |
| Fine-tuning | [plain-language-notices](https://github.com/adamselzer/plain-language-notices) |

## Run it

```bash
python3 -m http.server 8700   # then open http://localhost:8700
```

## Note on the stylesheet

`styles.css` is the **Civil** design system, copied here so the hub is self-contained.
Civil is authored and documented in
[benefits-intake-agent/DESIGN_SYSTEM.md](https://github.com/adamselzer/benefits-intake-agent/blob/main/DESIGN_SYSTEM.md);
in a production setup it would be a shared package rather than a copy.
