**Cuddly Spork**: An adventure in producing .docx and .pptx artifacts from .md sources. Also maybe some CI n' stuff.

## Create documents from templates

* **.docx** `pandoc --reference-doc templates/reference.docx -o document.docx sample_doc.md`

* **.pptx** `pandoc --reference-doc templates/reference.pptx -o presentation.pptx sample_ppt.md`
