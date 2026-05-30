# Pokemon GO Guide

A beginner's guide I wrote for my friend Jay who just started playing. Covers the stuff that actually matters — catching mechanics, IVs, type effectiveness, shadow pokemon, raids, and the resource economy — with actual math instead of vague advice.

Built with Quarto. The HTML version has interactive graphs, the PDF is for offline reading.

## Reading it

- **[guide.html](guide.html)** — open in a browser, has the graphs and dark theme
- **[guide.pdf](guide.pdf)** — printable version

## Building from source

```bash
quarto render guide.qmd --to html
quarto render guide.qmd --to pdf
```

Needs Quarto + Python with matplotlib/numpy.
