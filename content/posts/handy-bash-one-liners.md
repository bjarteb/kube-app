---
title: "Handy bash one-liners"
date: 2018-02-05T22:40:52+01:00
draft: true
---

Search for 'some-string' in working directory '.'

```bash
find . -type f -exec grep -i 'some-string' {} \; -print
```

Delete a LOT of files (if rm *.aud cannot handle the amount of files)

```bash
find . -name '*.aud' -type f -delete
```

