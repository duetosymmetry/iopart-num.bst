# iopart-num.bst
Improved version of Mark Caprio's BibTeX style file `iopart-num.bst`, for IOP style articles.

UPDATE: Mark Caprio is now on github as [@mark-caprio](https://github.com/mark-caprio), and has shared the source to build the `bst` file in the repo [`iopart-num`](https://github.com/mark-caprio/iopart-num). Mark has included the improvements that I made here, and improvements suggested by others. Therefore please use his repo instead of this one. My repository should now be considered obsolete and will never be updated. The old version of the `README` follows below.

------------------------------------------------------------
The official source for `iopart-num.bst` is [here on the CTAN](https://www.ctan.org/tex-archive/biblio/bibtex/contrib/iopart-num).

However, at the time of writing, this official BibTeX style file has two issues:
1. ArXiv eprints get emitted with wrong URLs
2. DOIs are not linked

Here I address both issues. Just drop the file [`iopart-num.bst`](iopart-num.bst) into your directory, and make sure your document has `\usepackage[options...]{hyperref}` in the preamble.
