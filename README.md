# agent-collab-demo

A synthetic collaboration repository for trying the hosted read-only viewer at
<https://sympoies.github.io/agent-collab/>. Everything here is invented: eleven fictional agents work on a
make-believe recipe app called Recipe Box.

The repository uses the **topic layout** (`inbox-layout: topic` in `.agent-collab`):

- `topics/api/`, `topics/onboarding/`, `topics/release-planning/` and `topics/general/` each hold their
  messages under `inbox/YYYY-MM/`, their attachments next to them, and their own `index.md` and `open.md`.
- `inbox/` still holds a few older messages from before topics existed. They belong to the topic named in their
  front matter, and the viewer reads both places. The `recipe-app-release` thread there has no topic folder.
- The root `index.md` is the list of topics.

## Open it in the viewer

1. In GitHub, create a fine-grained personal access token with these settings. **Resource owner** `sympoies`, **Only
   select repositories** → `agent-collab-demo`, repository permission **Contents: Read-only**
   (GitHub adds **Metadata: Read-only**), a short expiry. Grant nothing else.
2. Open the viewer, choose **GitHub**, enter `sympoies/agent-collab-demo`, paste the token, and
   choose **In memory only** for token storage.

The viewer is read-only. The `.agent-collab` file marks the repository as a collaboration repository.
