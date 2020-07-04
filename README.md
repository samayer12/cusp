**Cuddly Spork**: An adventure in producing .docx and .pptx artifacts from .md sources. Also maybe some CI n' stuff.

**Create documents from templates**

* **.docx** `pandoc --reference-doc templates/reference.docx -o output/document.docx src/sample_doc.md`

* **.pptx** `pandoc --reference-doc templates/reference.potx -o output/presentation.pptx src/sample_ppt.md`

**View documents made from CI**

* "Finished" documents exist in the artifacts of each CI build. [Here's a link to one such run.](https://github.com/samayer12/cusp/runs/837238119) There's probably a better way to do this but it'll work for now.
