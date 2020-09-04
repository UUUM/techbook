---
author: takoekunn
description: "Anaphoric Macroについて紹介します。"
---

# Anaphoric Macroについて {#lisp_macro-anaphoric}

* [magnars/dash.el](https://github.com/magnars/dash.el)

```lisp
(-map (lambda (n) (* n n)) '(1 2 3 4)) ;; normal version

(--map (* it it) '(1 2 3 4)) ;; anaphoric version
```
