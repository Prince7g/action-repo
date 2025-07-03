# Action Repo – action-repo

This repo is used to simulate GitHub actions (Push, Pull Requests, Merge) which send webhook data to the Flask server (webhook-repo).

## Usage

1. Clone this repo and make changes (e.g., push or pull request).
2. GitHub Actions will POST the event data to the configured webhook.
3. Make sure the webhook URL is correct in `.github/workflows/webhook.yml`
