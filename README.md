# 3D Walkabout client demos

Public HTML builds for sharing interactive examples with clients, hosted on GitHub Pages.

**Base URL:** https://3dwalkabout.github.io/public/

Each example must live in its own folder. Its client URL is the base URL followed by the folder name and a trailing slash.

For example, `isuzu/index.html` is available at **https://3dwalkabout.github.io/public/isuzu/**.

```text
README.md
isuzu/
  index.html
  assets/
  models/
  textures/
another-example/
  index.html
  assets/
```

- Add a separate folder for every new example; keep demo files out of the repository root.
- Upload the complete production build, including its `index.html`, scripts, styles, models and textures. Keep application source in the project's source repository.
- Use relative asset paths such as `./assets/` so the demo works inside its folder. For Vite, build with `--base=./`.
- Use short, lowercase folder names for new examples. URLs are case-sensitive; preserve existing folder names and links.
- Keep asset credits and third-party licenses with each build.
- When updating an example, replace only that example's build files.
- Commit to `main`, then wait for the GitHub Pages deployment to succeed and check the live URL before sharing it with clients.
