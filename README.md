# go2-view

Static HTML lesson previews from the [GO2_celta](https://github.com/egregor-io/GO2_celta) factory (teacher + student views, unit exam teacher keys).

- **Site:** [go2-view.vercel.app](https://go2-view.vercel.app)
- **Source:** factory local `preview/` via `python scripts/render.py --publish` / `--publish-only`
- **Deploy:** push to `main` → Vercel redeploys

This is the **only** HTML publish target for factory QA. Set `PREVIEW_REPO_PATH` to this clone in the factory `.env`.

Current contents: **Book 7** (units 1–12).
