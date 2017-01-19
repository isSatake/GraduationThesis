# Gyaon

[論文PDF](https://stkay.github.io/GraduationThesis/main.pdf)

## 概要

TBD

## PDFの生成

```
  % make
```

または

```
  % platex -kanji=utf8 main
  % pbibtex -kanji=utf8 main
  % platex -kanji=utf8 main
  % platex -kanji=utf8 main
  % dvipdfmx -p a4 main
  % open main.pdf
```
