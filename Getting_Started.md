
- [GitHub Quick Start](#github-quick-start)
  * [Basic syntax and writing tips](#basic-syntax-and-writing-tips)
  * [Generating Table of Contents in Markdown Files](#generating-table-of-contents-in-markdown-files)
    + [Semi-Automatic Method](#semi-automatic-method)
    + [Manual Method](#manual-method)
    + [Additional Resources](#additional-resources)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# GitHub Quick Start 

Welcome to the Getting Started guide! Whether you're new to GitHub or looking to brush up on your skills, this document will provide you with essential information to kickstart your journey. From setting up your first repository to mastering Markdown formatting and collaborating with others, we've got you covered. Let's dive in and explore the basics of getting started with GitHub.

## Basic syntax and writing tips

[Start here.](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

## Generating Table of Contents in Markdown Files

### Semi-Automatic Method

Using `gh-md-toc`

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

<small><i><a href='https://github.com/kmt555/OmicsResponseHub/blob/main/bulk_RNAseq/datasets.md'> This is an example of how this looks like.</a></i></small>

### Manual Method

Another option is to use an online web application. Simply copy and paste the content of your `file.md` into the tool. Ensure that your content is well-organized with dividers using `#` headers. The tool will parse this information and automatically generate a Table of Contents (TOC) for you. Once generated, copy the TOC and paste it into your `file.md` at the desired location. This method is particularly useful if you prefer a more visual and interactive approach to creating TOCs.

For example, Table of contents at the top of this page was generated with<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'> markdown-toc</a></i></small>.

### Additional Resources

(https://stackoverflow.com/questions/18244417/how-do-i-create-some-kind-of-table-of-content-in-github-wiki)
