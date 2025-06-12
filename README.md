## LaTeX Introduction

<img src="qr-link.png" width="300"/>

https://github.com/jeremyworsfold/LaTeX-Tutorial

copy and paste the `.tex` files in LaTeX directory into **www.overleaf.com**

---

## Other resources

If you've never used LaTeX before definitely take a look at this:
[Overleaf LaTeX introduction](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)

The examples 04 and 05 come from here:
[Tutorial/reference for RevTeX documentclass](https://www.overleaf.com/latex/templates/revtex-4-dot-2-template-and-sample/yydsrzvrqrzs)

---

## A minimal working example

See `01-mwe.tex` to learn about LaTeX commands and how to input:
- Paragraphs
- Equations
- Figures


**Have a go for yourself!**

---

## Get familiar with Overleaf

Makes starting out a lot easier (easier to see and correct errors)

Use toolbar or tab complete for:
- figures
- symbols
- tables

**Look around at the tools available**

---

## LaTeX exists outside of Overleaf!

You can download LaTeX (MikTex, TeXLive) to your computer and run it locally using tools like:
- VSCode with LaTeXWorkshop extension
- LaTeXWorksop
- TeXShop

---


## Columns and margins

See `02-columns.tex` for:
- `twocolumn` document class option
- `geometry` package for margins

---

## Document classes

Other documentclasses give you different things out-of-the-box:
- `article`: Standard and default
- `revtex4-2`: used by the American Physics Society (APS) journals and others. *Might* be exactly the style your lecturers are used to and want you to produce
- `book`: longer format with `\chapter{}` defined
- `memoir`: similarly long format, higher learning curve but nice aesthetics

**Take a look at the `03-revtex.tex` example**

---

## Citations

I recommend using `natbib`

Make sure you set the `\bibliographystyle{}`, then have `\bibliography{name}` at the end, generally before any appendices

Reference managers can help with `.bib` files but always check them

**Tip: wrapping text with {} brackets ensures words stay capitalized**

---

## Report Structure

What should go in the:
- introduction
- abstract
- discussion/conclusions

---

**Introduction**
- **context**: what is the subject of the paper and what's been done previously? Why is this interesting in Physics?
- **need**: why was this experiment necessary?
- **task**: what have you done?
- **object**: preview the paper

**Abstract**

context, need, task, object, *implication*


---

### Other Packages

- **`physics`:** Useful for mathematics typesetting, e.g. integrals and partial derivatives
- **`cleveref`**: Automatic addition of "Section", "Appendix", "eq." etc
- **`microtype`**: Adjusts spacing of characters slightly to avoid awkward line breaks
- **`mathtools`**: for more niche symbols
- **`titlesec`**: adjust section formatting
- [**`listings`:**](https://www.overleaf.com/learn/latex/Code_listing) Enter code snippets as text or load from a file

