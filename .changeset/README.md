# Changesets

One Markdown file per change, with the packages it bumps in the front matter (`livekit`, `livekit-api`, `livekit-protocol`):

```md
---
livekit: minor
---

Short description for the changelog.
```

`verwalter pr` turns pending files into a release PR; the file is deleted when it merges.
