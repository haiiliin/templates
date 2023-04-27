# Templates for jtex

This repository contains templates for [jtex](https://myst-tools.org/docs/jtex).

## Usage

Install [MyST Command Line Tools](https://myst-tools.org/docs/mystjs/quickstart), edit the `paper.md` file, and 
run the following command to build the paper in docx, TeX and PDF formats:
```shell
myst build paper.md --docx --tex --pdf
```
You are required to have a [LaTeX](https://www.latex-project.org/get/) distribution installed on your computer if you 
want to build the paper in the PDF format.

You can click `Use this template` button to create a new repository from this template and start writing your paper.
More templates can be found with `myst templates list` command, and possible options for a specific template can be found
with `myst templates list <template-name> --tex` command. For more details, see the 
[myst-templates](https://github.com/myst-templates) organization.
