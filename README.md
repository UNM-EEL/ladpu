# Los Alamos Home Energy Tools (UNM Energy Econ Lab)

Interactive tools from the working paper *Pathway to Zero Natural Gas*, on residential
electrification in Los Alamos, NM.

- **County-wide projection** — [unm-eel.github.io/ladpu](https://unm-eel.github.io/ladpu/)
  (`index.html`): how much electricity and natural gas Los Alamos homes would use through 2070
  as households replace gas appliances with electric ones, under three scenarios with solar.
- **Household calculator** — [unm-eel.github.io/ladpu/house.html](https://unm-eel.github.io/ladpu/house.html)
  (`house.html`): a "should I switch?" tool for a single home — pick your gas appliances, choose
  what to electrify, optionally add rooftop solar, and see the change to your electricity use,
  gas use, and annual bill under the current LADPU rates.

Both pages are fully self-contained (Chart.js and all model data are embedded), so they need
no build step, no server, and no internet connection. Served via GitHub Pages from the repo root;
the host `unm-eel.github.io` is left free for the lab's main page.

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
