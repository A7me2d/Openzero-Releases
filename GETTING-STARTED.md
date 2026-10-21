# Getting started

## Install and connect

Download the `.exe` from the [latest release](https://github.com/A7me2d/Openzero-Releases/releases/latest), run it and activate Open Zero with a valid key.

In **Settings → Connections & updates**, enable your chosen provider. Install its required local tool and sign in through that tool. Provider subscriptions and model access are separate from Open Zero activation. A listed model is not a guarantee of free access.

## Start a conversation

Select a project folder, create a conversation, choose an available model and review its permissions. Open files from the explorer to edit while keeping the chat nearby.

## Create a Super Agent team

1. Switch to **Super Agent** and create a team.
2. Assign the Brain to a supported, connected provider.
3. Add worker desks; choose their roles, providers, conversations and project folders.
4. Give the Brain a clear request, acceptance criteria and the desks it may use.
5. Follow actual results and review changed files before approving the outcome.

For parallel coding, assign distinct file ownership or isolated projects to reduce editing conflicts.

## Connect memory

Open **Core-Brain** and connect your local knowledge repository. Review proposals before approval. Keep credentials and full private conversations out of knowledge files. Connecting memory does not automatically upload it to GitHub; backup requires an explicit commit and push.

## Troubleshooting

| Problem | First check |
| --- | --- |
| Provider unavailable | Its tool is installed, authenticated and enabled. |
| Model missing | The provider's available/enabled models; refresh the connection. |
| Activation blocked | Key validity, request balance and device allowance. |
| Update unavailable | Download the latest installer manually. |
| Extension inactive | Compatibility; not every VS Code API is supported. |

Check updates in **Settings → Connections & updates**. If a problem continues, [open an issue](https://github.com/A7me2d/Openzero-Releases/issues/new) with reproducible steps and redacted diagnostics.
