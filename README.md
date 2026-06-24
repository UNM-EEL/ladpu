# Los Alamos Home Energy Tools (UNM Energy Econ Lab)

Interactive tools from the working paper *Pathway to Zero Natural Gas*, on residential
electrification in Los Alamos, NM.

The landing page at [unm-eel.github.io/ladpu](https://unm-eel.github.io/ladpu/) (`index.html`) links to
three interactive tools:

- **County energy projection** (`projection.html`): how much electricity and natural gas Los Alamos
  County homes would use through 2070 as households replace gas appliances with electric ones, under
  three scenarios with rooftop solar and 95% uncertainty bands.
- **Home electrification calculator** (`house.html`): a "should I switch?" tool for a single home —
  pick your gas appliances, choose what to electrify, optionally add rooftop solar, and see the change
  to your electricity use, gas use, and yearly energy bill under current LADPU rates.
- **Program willingness to pay** (`dce.html`): a utility-facing tool from the discrete choice experiment —
  set a program's carbon-reduction, efficiency, and rebate levels and the target population, and see the
  predicted average household stated willingness to pay.
- **Solar rebound & carbon** (`solar.html`): a utility-facing tool from the solar-rebound analysis —
  enter the number of solar adopters and a grid emission factor, and see the electricity load reduction,
  natural-gas change, and CO2 reduction, with the rebound effect made explicit.

Every page is fully self-contained (Chart.js and all numbers are embedded), so they need no build step,
no server, and no internet connection. Served via GitHub Pages from the repo root; the host
`unm-eel.github.io` is left free for the lab's main page.

## License

© 2024–2026 Yuting Yang and Jamal Mamkhezri.

This work is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0
International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). You may
share it with attribution, for non-commercial purposes, without modifications. See [`LICENSE`](LICENSE)
for the full terms.

## Citation

If you use these tools or the underlying analysis, please cite:

```bibtex
@techreport{yang2026pathway,
  title       = {Pathway to Zero Natural Gas},
  author      = {Yang, Yuting and Mamkhezri, Jamal and Jawhari, Ahmed A. and
                 Zhao, Jiaqing and Cornelius, Benjamin},
  year        = {2026},
  institution = {University of New Mexico},
  type        = {Working Paper},
  address     = {Albuquerque, NM},
  note        = {Interactive tools: \url{https://unm-eel.github.io/ladpu/}}
}
```

> Yang, Y., Mamkhezri, J., Jawhari, A. A., Zhao, J., & Cornelius, B. (2026).
> *Pathway to Zero Natural Gas*. Working Paper, University of New Mexico.
