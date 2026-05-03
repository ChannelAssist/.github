# ChannelAssist `.github` (public)

This **public** repository hosts the ChannelAssist organization profile rendered at https://github.com/ChannelAssist for **anonymous and non-member visitors**.

The visible content lives at [`profile/README.md`](profile/README.md).

## Two-repo split

| Repo | Visibility | Profile rendered to |
|---|---|---|
| `.github` (this repo) | **public** | anonymous + non-member visitors |
| `.github-private` | private | signed-in ChannelAssist members |

GitHub's rendering precedence: members see `.github-private` (the rich version with internal repo landscape, onboarding deep-dive, bridge architecture); non-members see `.github` (this repo, intentionally sanitized).

## Maintenance rules

- **Keep `profile/README.md` sanitized.** Internal repo names, infrastructure references, SDLC specifics, AB# / bridge / Project numbers, and deployed-site URLs belong in `.github-private`, not here.
- **Keep this repo public.** Making it private silently stops rendering on the org page for non-members.
- **Keep the file at `profile/README.md`.** GitHub reads only that path; anywhere else and it stops rendering.

If you need to update the public profile, edit `profile/README.md`, open a PR, and merge.
