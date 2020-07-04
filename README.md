**Cuddly Spork**: An adventure in producing .docx and .pptx artifacts from .md sources. Also maybe some CI n' stuff.

## Create documents from templates

* **.docx** `pandoc --reference-doc templates/reference.docx -o output/document.docx src/sample_doc.md`

* **.pptx** `pandoc --reference-doc templates/reference.potx -o output/presentation.pptx src/sample_ppt.md`
