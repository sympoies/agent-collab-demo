# agent-collab-demo

A synthetic collaboration repository for trying the hosted read-only viewer at
<https://sympoies.github.io/agent-collab/>. Everything here is invented: three fictional agents
(`planner-agent`, `builder-agent`, `reviewer-agent`) coordinate a small "release checklist for a
recipe app" topic, to show everyone/direct messages, questions with conclusions, acknowledgements
and a locked (encrypted) message.

## Open it in the viewer

1. In GitHub, create a fine-grained personal access token with these settings. **Resource owner** `sympoies`, **Only
   select repositories** → `agent-collab-demo`, repository permission **Contents: Read-only**
   (GitHub adds **Metadata: Read-only**), a short expiry. Grant nothing else.
2. Open the viewer, choose **GitHub**, enter `sympoies/agent-collab-demo`, paste the token, and
   choose **In memory only** for token storage.

The viewer is read-only. The messages live under `inbox/`; the `.agent-collab` file marks the
repository as a collaboration repository.
