# OSCP Exam Report Template in **Markdown**

**whoisflynn improved template v3.2**

![](https://i.imgur.com/Z344YCQ.png)
![](https://i.imgur.com/wegbNYr.png)

**Official Offensive Security Template v1**

![](https://i.imgur.com/9zoWFfr.png)
![](https://i.imgur.com/cv5qW8Z.png)

## Requirements

- [Pandoc](https://pandoc.org/installing.html)
- LaTeX (eg. [TeX Live](http://www.tug.org/texlive/)) in order to get `pdflatex` or `xelatex`
- [Eisvogel Pandoc LaTeX PDF Template](https://github.com/Wandmalfarbe/pandoc-latex-template#installation)

## Usage

Write your report in **markdown**.

Generate the report PDF from the markdown template:

```
pandoc OSCP-exam-report-template_whoisflynn_v3.2.md -o OSCP-OS-XXXXX-Lab-Report.pdf --from markdown+yaml_metadata_block+raw_html --template eisvogel --table-of-contents --toc-depth 6 --number-sections --listing --top-level-division=chapter
```

## Color sets

Well rendering color sets you can use in the template YAML frontmatter:

titlepage-color          | titlepage-text-color | titlepage-rule-color
-------------------------|----------------------|---------------------
`DC143C` (Crimson)       | `FFFFFF` (White)     | `FFFFFF` (White)
`00FF7F` (SpringGreen)   | `006400` DarkGreen   | `000000` (Black)
`1E90FF` (DodgerBlue)    | `FFFAFA` (Snow)      | `FFFAFA` (Snow)
`483D8B` (DarkSlateBlue) | `FFFAFA` (Snow)      | `FFFAFA` (Snow)
`FFD700` (Gold)          | `000000` (Black)     | `000000` (Black)
`FFEFD5` (PapayaWhip)    | `000000` (Black)     | `000000` (Black)
`FF8C00` (DarkOrange)    | `000000` (Black)     | `000000` (Black)
`FFEF96` (no name)       | `50394C` (no name)   | `50394C` (no name)

## Credits

Report Templates:

- Official Offensive Security Template v1 (UNLICENSED): https://support.offensive-security.com/oscp-exam-guide/#suggested-documentation-templates
- whoisflynn improved template v3.2 (UNLICENSED): https://github.com/whoisflynn/OSCP-Exam-Report-Template

Pandoc Template

- Eisvogel ([LICENCE](https://github.com/Wandmalfarbe/pandoc-latex-template/blob/master/LICENSE)): https://github.com/Wandmalfarbe/pandoc-latex-template
