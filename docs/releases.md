---
title: Release branches
---

# Release branches

```mermaid
graph TD
    D["Dev Branch (Internal)"] -->
    C{Canary}
    P["Alpha Branch (Public)"] --> C
    C --> B["Public beta"] --> S["Stable"]
```
