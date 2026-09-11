# Royal Finance

An inbound voice agent for credit-card servicing, built on the Wonderful platform.

## Where the agent lives

**https://fde-onboarding.app.sb.wonderful.ai/workspace/fb6f980e-c093-5b02-a530-c0c126324af0/agent-studio-v2**

Everything that runs is there, not here: the agent itself — prompts, skills, tools, tags and metrics —
along with the Wonderful Functions it calls, the custom tables those read and write, the knowledge
base it answers product questions from, and the back-office app over the dispute queue.

## What is in this repository

| Folder | Contents |
| --- | --- |
| `diagrams/` | architecture diagrams: structure and entry, the data model, and one per skill |
| `presentation/` | the walkthrough deck |

## Opening the diagrams

They are draw.io files with uncompressed XML, so any of these works:

- **In the browser** — download the `.drawio` file, then open [app.diagrams.net](https://app.diagrams.net)
  and choose *Open Existing Diagram*. Opening the file straight from GitHub's preview will not work:
  GitHub renders it as XML.
- **On the desktop** — the [draw.io app](https://www.drawio.com/), with *File → Open*.
- **In VS Code** — the *Draw.io Integration* extension renders a `.drawio` file in place, so cloning
  the repository is enough.

Each diagram names the decision records behind it. The running agent is the authority, though: where a
drawing and the code disagree, the code is right.
