<p align="center">
  <img src="MeritLogo.png" alt="MeRIT" width="300">
</p>

<div align="center">
 <h1>MeRIT</h1>
 <p><i>Method Reporting with Initials for Transparency</i></p>
</div>

<!-- badges: start -->
[![DOI](https://img.shields.io/badge/DOI-10.1038%2Fs41467--023--37039--1-blue)](https://doi.org/10.1038/s41467-023-37039-1)
[![Website](https://img.shields.io/badge/website-merit.help-brightgreen)](http://www.merit.help/)
[![Content: CC BY 4.0](https://img.shields.io/badge/content-CC%20BY%204.0-green)](LICENSE.md)
<!-- badges: end -->


Welcome to MeRIT! Head over to the [MeRIT website](http://www.merit.help/) for
more information.

This repository contains the source for that website.

## What is MeRIT?

Author contribution statements have improved over the last decade, but they still
work at the wrong resolution. A CRediT statement tells you that four authors
contributed to "Investigation". It does not tell you *who did which part* — who
ran the field season, who did the assays, who wrote the model.

MeRIT is a simple proposal to fix that: **put author initials directly in the
Methods section**, next to the methods those authors actually performed.

> Beetles were reared at 30 °C (EIC) and body mass recorded at eclosion (SN, MJG).

That is the whole idea. It costs nothing, requires no journal infrastructure, and
can be adopted by any author team unilaterally. It makes contributions
**granular** — which specific task — and **accountable**, because the credit sits
where a reader can check it against the work. MeRIT complements CRediT rather
than replacing it: CRediT gives the high-level taxonomy, MeRIT gives the detail
at point of use.

## The website

| Page | Contents |
| :--- | :------- |
| [Benefits](Benefits.md) | The six benefits of MeRIT, with worked figures |
| [Community Examples](Community_Examples.md) | Published papers that use MeRIT |
| [FAQ](FAQ.md) | Common questions and objections |
| [MeRIT People](MeRITPeople.md) | People behind and endorsing MeRIT |
| [Contribute](Contribute.md) | How to get involved |
| [Cite](Cite.md) | How to cite MeRIT |

The site is a [Jekyll](https://jekyllrb.com/) build using the `minima` theme,
deployed via GitHub Pages with a custom domain. Navigation order is set by
`header_pages` in `_config.yml`.

```text
MeRIT/
├── index.md                # landing page
├── Benefits.md
├── Community_Examples.md
├── FAQ.md
├── MeRITPeople.md
├── Contribute.md
├── Cite.md
├── _config.yml             # Jekyll config and nav order
├── _layouts/               # home and post layouts
├── _includes/              # head, header, footer partials
├── CNAME                   # www.merit.help
├── MeritLogo.png
└── merit_fig1.png, merit_fig2.png
```

## Contributing

Contributions are welcome, and the most useful ones are not code:

- **Add your paper.** If you have used MeRIT in a publication, add it to
  `Community_Examples.md`. Real examples are the most persuasive argument the
  site has.
- **Improve the FAQ.** If you hit an objection MeRIT does not yet answer — from a
  co-author, an editor, or a reviewer — that question belongs in `FAQ.md`.
- **Fix the site.** Typos, broken links, and layout issues via issue or pull
  request.

See [Contribute.md](Contribute.md) for more. To build locally:

## How to cite MeRIT

There are several methods by which you can acknowledge the use of the MeRIT
system in your paper. For instance, in your Methods, Acknowledgements, or Author
Credit sections you could simply write:

> "We provide author initials as per the MeRIT system (Nakagawa et al. 2023)."

*or*

> "EIC conducted the fieldwork (note we use the MeRIT system as per Nakagawa et
> al. 2023)."

**Full citation:**

> Nakagawa, S., Ivimey-Cook, E. R., Grainger, M. J., O'Dea, R. E., Burke, S.,
> Drobniak, S. M., Gould, E., Macartney, E. L., Martinig, A. R., Morrison, K.,
> Paquet, M., Pick, J. L., Pottier, P., Ricolfi, L., Wilkinson, D. P., Willcox, A.,
> Williams, C., Wilson, L. A. B., Windecker, S. M., Yang, Y., & Lagisz, M. (2023).
> Method Reporting with Initials for Transparency (MeRIT) promotes more
> granularity and accountability for author contributions. *Nature
> Communications*, 14, 1788. <https://doi.org/10.1038/s41467-023-37039-1>

## Related work

- [**TADA**](https://github.com/EIvimeyCook/TADA) — guidelines for improving
  analytical code sharing
- [**DCQC**](https://github.com/EIvimeyCook/DCQC) — SORTEE data and code quality
  control checklist
- [**SORTEE**](https://www.sortee.org/) — Society for Open, Reliable, and
  Transparent Ecology and Evolutionary Biology
