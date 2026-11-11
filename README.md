# Markdown2Word

pandocを使ってmarkdownをwordにする。

wordにする際にテンプレートを使用して体裁を整える。

コマンドは以下の通り。

```
pandoc input.md --reference-doc=custom-reference_md2word.docx -o output.docx
```

ymlを使うこともできる。

```
pandoc -d make.yml
```