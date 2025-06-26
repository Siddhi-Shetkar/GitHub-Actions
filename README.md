# GitHub Actions Workflow: Node.js Hello Logger

This repository contains a basic GitHub Actions workflow that demonstrates how to:

- Set up a Node.js environment using `actions/setup-node`
- Run a custom shell command inside the workflow
- Log a custom message to the GitHub Actions console

## Workflow Summary

- **Trigger:** On every `push` to the repository
- **Runs on:** `ubuntu-latest`
- **Steps:**
  1. Checks out the repository
  2. Sets up Node.js (v18)
  3. Logs the message:  Hello from @siddhishetkar

This is a test push to trigger GitHub Actions.
