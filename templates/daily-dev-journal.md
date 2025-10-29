---
title: "{{title}}"
date:
tags:
  - daily-dev
---

## 🧠 Context

What were you working on today? What problem, curiosity, or challenge led you here?

> Example: “While setting up linting for a nested Vue project inside a Laravel repo, I hit a strange issue where lint-staged couldn’t find .git.”

---

## 🔍 Discovery

What did you learn, figure out, or realize? Explain it like you’re writing to _future you_ who might face this again.

> Example: “Turns out lint-staged assumes it’s running from the Git root. Since my frontend lives in a subfolder, I had to set `gitDir` manually.”

---

## 🧩 Snippet / Example

Keep it short — just the key code, config, or command that illustrates the point.

```bash
npx lint-staged --cwd ./frontend

```
