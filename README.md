[battletech-tw]: https://store.catalystgamelabs.com/products/battletech-total-warfare-pdf
[battletech-as]: https://store.catalystgamelabs.com/products/battletech-alpha-strike-commanders-edition

[ci-badge]:  https://github.com/Eudicods/mercenarys-pride/workflows/Deploy/badge.svg
[ci-link]:   https://github.com/Eudicods/AstralSea/actions
[web-badge]: https://img.shields.io/badge/website-live-blue
[web-link]:  https://mercenarys-pride.jeremylt.org

[cc-by-nc-sa]:       https://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-badge]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png

## Mercenary's Pride

[![CI Status][ci-badge]][ci-link]
[![Website][web-badge]][web-link]
[![CC BY-NC-SA 4.0][cc-by-nc-sa-badge]][cc-by-nc-sa]

Mercenary's Pride is a retelling of Jane Austin's Pride and Prejudice as a series BattleTech scenarios highlighting the major events in the book.
Commanders play scenarios in multiple formats, such as [BattleTech][battletech-tw] and [Alpha Strike][battletech-as].

### Building Locally

To build locally, you need `Python3` and `pip`

First install the dependencies for building the website
```
pip install -r requirements.txt
```

Then build the website
```
make html
```

The local website will be in `build/html`

## License

Catalyst Game Labs has the rights to BattleTech.
Anything that's in this repository that can be licensed is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]
