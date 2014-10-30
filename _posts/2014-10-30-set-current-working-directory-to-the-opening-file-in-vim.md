---
layout : post
title  : Set current working directory to the opening file in Vim
---
Use the command:

```
:lcd %:p:h
```

Explanation:

- **%**: the name of the current file
- **%:p**: full path
- **%:p:h**: directory

**Note**:

- **cd** sets the current directory for all windows in Vim
- **lcd** sets the current directory for the current window only.

