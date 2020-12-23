This is a very minimal implementation of an [org babel](https://orgmode.org/worg/org-contrib/babel/languages/index.html) file for the [GAP](https://www.gap-system.org/)
algebra system modified from the template file. This allows the evaluation of GAP code blocks in org:

```
#+begin_src gap
    G := DihedralGroup(8);
    Print(StructureDescription(Center(G)));
#+end_src

#+RESULTS:
:  <pc group of size 8 with 3 generators>
:  > C2
```

This assumes that the [GAP major mode](https://melpa.org/#/gap-mode)
is installed.
