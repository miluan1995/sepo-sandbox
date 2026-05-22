# Agent Capability Smoke Test

- This sandbox smoke test confirms the Sepo Agent can make a real repository change through the Codex and OpenAI-compatible relay path.
- The agent can read GitHub issue context, including comments and acceptance criteria, before editing the repository.
- The agent can inspect local project files and memory context to keep a small requested change aligned with repository conventions.
- The agent can create a focused documentation artifact without modifying production behavior.
- The agent can avoid workflow, configuration, secret, and dependency changes when the task explicitly excludes them.
- The agent can leave a minimal working-tree change ready for the surrounding GitHub Actions workflow to commit and open as a pull request.
