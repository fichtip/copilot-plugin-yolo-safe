# Copilot YOLO Safe Plugin

A GitHub Copilot CLI plugin that replicates `/yolo` behavior
but **prevents commits**.

## Features

- ✅ Autonomous repo-wide changes
- ✅ Full tool usage (read/edit/bash)
- ✅ Multi-step task execution
- ❌ No commits (blocked via hooks)

## Install

```bash
copilot plugin install your-username/copilot-yolo-safe
```

## Usage

```bash
copilot /agent yolo-safe
```

## Optional alias

```bash
alias yolo-safe='copilot /agent yolo-safe'
```

## Safety

All `git commit` commands are blocked at runtime.

## Customize

Edit:
- `agents/yolo-safe.agent.md` → behavior
- `hooks.json` → safety rules
