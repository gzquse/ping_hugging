# Ping Hugging Face Space

This repository uses a GitHub Actions workflow to periodically ping a Hugging Face
Space so it stays warm.

## Setup

1. Confirm the Space URL in `.github/workflows/ping.yml` (default:
   `https://huggingface.co/spaces/qcsyn/rubriq-demo`).
2. Ensure GitHub Actions are enabled for the repository.
3. Update the cron schedule in `.github/workflows/ping.yml` if you want a
   different ping frequency.
4. Trigger the workflow manually: **Actions** → **Ping Hugging Face Space** →
   **Run workflow** (optionally override the Space URL input).
5. Verify the Space is active by loading the URL after the workflow completes.
