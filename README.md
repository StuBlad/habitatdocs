
# habitatdocs
### Development documents from Lucasfilm's Habitat converted to modern formats

This is a collection of all of the documentation and notes I could find from the [original Lucasfilm Habitat document archives](https://github.com/Museum-of-Art-and-Digital-Entertainment/habitat/tree/master/chip/habitat/docs).

My goal is to convert all of these to modern formats that are more easily readable, as the majority of them were created using *troff*.

For the text files that weren't typeset for *troff* and have no formatting, I have used the [text2pdf](http://www.eprg.org/pdfcorner/text2pdf/) utility in Windows.

However, it would look a lot better to recreate these plain text files into a properly typeset *troff* file. You can do this by taking an existing file from the original Habitat archives to understand the formatting, editing a plain text file to add them in and then run the following command:

> groff -ms filename.itr | ps2pdf - filename.pdf

If you would like to format some of the plain text files into *troff*, add your completed work to the ***new*** folder in both *.itr* and *pdf* formats and feel free to submit a pull request.

## Documents with issues at this time (12/28/20)
The following documents will not convert cleanly using the above command at this time and are missing from this repository.

* congrats.itr
* ghu.itr
* ghu.itr.aug6
* ghuguide.itr
* objman.itr

If you are able to get these to output correctly, please submit them in PDF format with a pull request.