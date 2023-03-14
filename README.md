[![Linter](https://github.com/t4t5u0/latex2e-textlint-sample/actions/workflows/linter.yaml/badge.svg?event=workflow_run)](https://github.com/t4t5u0/latex2e-textlint-sample/actions/workflows/linter.yaml)

# late2e-textlint-sample
LaTeX2eに対して、TextLintを行いたいです．

`writing_space` 内に，TeXファイルなどを配置してください．  
手元でPDFを作成する際は以下のよう，`writing_space`内でPDFを作成してください．
```sh
cd writing_space
latexmk
```

pdfを出力する．
```
docker compose up pdf
```


linterを適用する．
```
docker compose up linter
```