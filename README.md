### Docsplit
---
https://github.com/documentcloud/docsplit

```ruby
docsplit images example.pdf
docsplit images docs/*.pdf --size 700x,50x50 --format gif --pages 3,10-15,42
Docsplit.extract_images('example.docs', :size => '1000x', :format => [:png, :jpg])

docsplit text path/to/doc.pdf --pages all --language deu
docs = Dir['storage/originals/*.doc']
Docsplit.extract_text(docs, :ocr => false, :output => 'storage/text')

docsplit pages path/to/doc.pdf --pages 1-10
Docsplit.extract_pages('path/to/presentation.ppt')
Docsplit.extract_pages('doc.pdf', :pages => 1..10)

docsplit pdf documentation/*.html
Docsplit.extract_pdf('expense_report.xls')

docsplit title path/to/stooges.pdf
Docsplit.extract_length('path/to/stooges.pdf')
```

```
```

```
```
