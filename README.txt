PRE-REQUISITIES
You will need a working LaTeX installation. We recomend using pdflatex 
to process the files. You will also need biber installed. This is distributed 
as part of the latest versions of LiveTex and MikTex. If you have
problems please let us know.

THE DISTRIBUTION AND INSTALLATION
The distribution contains 2 folders: nowfnt and nowfnttexmf. 

If your LaTeX installation uses a localtexmf folder
you can copy the nowfnttexmf folder to the localtexmf
folder and make it known to your TeX installation. 
You can now proceed to use the class file as normal.

Alternatively, copy all the files in the folder nowfnt into
your working folder. You will also need to copy the file
<jrnl-code>-journaldata.tex from the folder nowfnt\journaldata
into your working folder.

<jrnl-code> is the 3-letter code of the journal which will be supplied by
your publisher. This code should also be used as an option to the \documentclass
in your dcoument.

For example:
\documentclass[OPT,biber]{nowfnt}

DOCUMENTATION
Basic documentation and a sample .tex file are in the folder:
nowfnt\SampleArticle. Read the FnTarticle.pdf
before starting to write.

QUESTIONS
Contact Anahita Gupta (anahita.gupta@nowpublishers.com) or
Mike Casey (mike.casey@nowpublishers.com).
