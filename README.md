# lazycode-legal

Public privacy policies and legal pages for Lazycode apps, served by GitHub Pages
at https://soumyasethy.github.io/lazycode-legal/. App code lives in private repos;
only these static pages are public.

These pages are generated. The policy text and the page template live in the
`lazycode-site` repo (`src/legal/*.html`, `scripts/legal.py`, `scripts/family.py`,
design rules in `DESIGN.md`). To change a policy, edit it there and run:

```bash
python3 scripts/legal.py ../lazycode-legal
```

Pages: Tumble, Rotmeter (redirect to its own site), NetSpeed, Curtain, Glint, and the developer page.
