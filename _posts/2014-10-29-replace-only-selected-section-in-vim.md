---
layout: post
title: Replace only selected section in Vim
---
First, select the section, then execute the following command:

```
:'<,'>s/%V{search_pattern}/{replace_pattern}/g
```

For example, replace space with non-breaking space:

```
:'<,'>s/%V\s/\&nbsp/g
```
