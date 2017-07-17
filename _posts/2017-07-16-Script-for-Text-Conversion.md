---
layout: post
title:  "Script for Text Conversion"
date:   2017-07-16
categories: [INLS]
---

The piece that I used to test my text conversion script was an early assignment from my ENGL 105 class.
It is my personal statement and introductory essay, which I decided to write about the two main places where I have lived in my life.


To get it into multiple formats, I wrote a script including Pandoc and TeXLive that converts an original file to six different formats
(including the original format): 
markdown, HTML, docx, odt, PDF, and txt. 
My script depends on the user entering in the information correctly, 
because it asks for both the file name (like "README") and the extension written without a period ("md").
However, if the user enters this information correctly, it will quickly duplicate into multiple different types of files using Pandoc.
The original file does not have to be in Markdown format. 


I was able to use my script successfully; here is my written work in six formats:
* [PDF](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.pdf)
* [DOCX](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.docx)
* [HTML](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.html)
* [ODT](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.odt)
* [TXT](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.txt)
* [MD](https://github.com/marhass/marhass-convert-documents/blob/master/ataleoftwocities.md)

Finally, [here](https://github.com/marhass/marhass-convert-documents/blob/master/marhass-convert-docs.sh) is the script that I used to create the files.