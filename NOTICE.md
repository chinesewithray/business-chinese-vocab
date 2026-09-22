# Third-party notices

This project is a self-contained static page. It bundles no third-party code at runtime.
The notices below cover development-time tools and cross-checked datasets.

## pinyin-pro

- Used at build time to generate the pinyin column.
- License: **MIT**
- Copyright (c) 2019-present zh-lx
- https://github.com/zh-lx/pinyin-pro

## cacl2

- Used as a cross-check source for the selection of business and financial Chinese terms.
- License: **Apache-2.0**
- Copyright (c) 2019-present limccn
- https://github.com/limccn/cacl2
- No cacl2 source code is redistributed here. The vocabulary list is an original
  compilation; the cacl2 term lists were consulted to validate coverage.

## rhcarvalho/cedict (CC-CEDICT)

- Evaluated as a source of English glosses. **Not used** in the final dataset
  (measured coverage of the business term candidates was only ~3%, so the glosses
  were written by the author instead).
- https://github.com/rhcarvalho/cedict
