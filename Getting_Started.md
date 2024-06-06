# Creating Table of Content in .md files

## Using `gh-md-toc`

Download the script and follow installation instructions as outlined here:
(https://github.com/ekalinin/github-markdown-toc/blob/master/README.md)

In my case, this was

```
curl https://raw.githubusercontent.com/ekalinin/github-markdown-toc/master/gh-md-toc -o gh-md-toc
chmod a+x gh-md-toc
```

Before use, make sure `gh-md-toc` is available in the PATH.

Per author's instructions, to insert TOC to your file.md, insert these two lines:

```
<!--ts-->
<!--te-->
```

And run in your terminal:

```bash
$ ./gh-md-toc --insert file.md
```

