# Easy security maps

This repository contains set of mindmaps and links helping students to obtain SOC-related knowledge as well as expirience with open-source and proprietary tools. 
We suggest to use ready virtual machines and distributions listed below:
1. [FLARE VM](https://github.com/fireeye/flare-vm/blob/master/README.md)
1. [REMnux](https://remnux.org)
1. [SIFT Workstation](https://digital-forensics.sans.org/community/downloads)

## Mind maps
1. [Email Analysis](#Email-analysis)
1. [MS Office Files Analysis](#MS-Office-Files-Analysis)
1. [PDF Files Analysis](#PDF-Files-Analysis)

### Email analysis

This mindmap shows what types of IOCs could be executed from suspicious email headers, content and attached files:
- string
- hash
- IP-address
- domain name
- host name

### MS Office Files Analysis

There is a list of open-source tools grouped by actions which can be executed with suspicious MS Office files (doc, docx, xls, xlsx, ppt, pptx etc.)

- [oletools (olevba, oledump, oleid, oleobj, rtfdump, rtfobj, mraptor, pyxwf)](https://github.com/decalage2/oletools)
- [officeparser](https://github.com/unixfreak0037/officeparser)
- [pyOLEScanner.py](https://github.com/Evilcry/PythonScripts)
- [hachoir-urwid](https://github.com/vstinner/hachoir/blob/master/doc/urwid.rst)

### PDF Files Analysis

There is a list of open-source and online tools grouped by actions which can be executed with suspicious PDF files

- [PDF Tools from Didier Stevens (pdf-parser.py, pdfid.py)](https://blog.didierstevens.com/programs/pdf-tools/)
- [peepdf.py](http://eternal-todo.com/tools/peepdf-pdf-analysis-tool)
- [PDF Stream Dumper](http://sandsprite.com/blogs/index.php?uid=7&pid=57)
- [PDFExaminer](https://www.malwaretracker.com/pdf.php)
