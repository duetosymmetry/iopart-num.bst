# iopart-num.bst
Improved version of Mark Caprio's BibTeX style file `iopart-num.bst`

The official source for `iopart-num.bst` is [here on the CTAN](https://www.ctan.org/tex-archive/biblio/bibtex/contrib/iopart-num).

However, at the time of writing, this official BibTeX style file has two issues:
1. ArXiv eprints get emitted with wrong URLs
2. DOIs are not linked

Here I address both issues. Just drop the file `iopart-num.bst` into your directory, and make sure your document has `\usepackage[options...]{hyperref}` in the preamble.
