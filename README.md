# Pokemon GO Guide

A beginner's guide I wrote for my friend Jay who just started playing. Covers the stuff that actually matters — catching mechanics, IVs, type effectiveness, shadow pokemon, raids, and the resource economy — with actual math instead of vague advice.

Built with Quarto. The HTML versions have interactive graphs and a dark theme, the PDFs are for offline reading.

## Reading it

| Language | HTML | PDF |
|----------|------|-----|
| English | [guide.html](guide.html) | [guide.pdf](guide.pdf) |
| Polski | [guide-pl.html](guide-pl.html) | [guide-pl.pdf](guide-pl.pdf) |
| 中文 | [guide-zh.html](guide-zh.html) | [guide-zh.pdf](guide-zh.pdf) |

Game terms (Berry, Shadow, Curveball, Hundo, etc.) stay in English across all versions, with native translations in parentheses on first use.

## Building from source

```bash
quarto render guide.qmd --to html
quarto render guide.qmd --to pdf
```

Same for `-pl` and `-zh` variants. Needs Quarto + Python with matplotlib/numpy.
