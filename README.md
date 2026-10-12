> [!WARNING]
> **Tento fork je archivovaný a už se neudržuje.** Používejte původní integraci
> [kukulich/home-assistant-aladin-online](https://github.com/kukulich/home-assistant-aladin-online).
> Od verze 3.0.0 (červen 2026) sama používá nové API ČHMÚ (`data-provider.chmi.cz`),
> kvůli kterému tento fork vznikl.
>
> Fork zadává místo souřadnic ID stanice. Obsahuje známou chybu: entita počasí spadne
> při porovnání časů s časovým pásmem a bez něj. Pokud ho máte v HACS, odeberte ho
> a nainstalujte upstream. Integrace se nastavuje znovu, protože upstream místo ID
> stanice používá souřadnice.
>
> *This fork is archived and unmaintained. Please use the upstream
> [kukulich/home-assistant-aladin-online](https://github.com/kukulich/home-assistant-aladin-online),
> which supports the new ČHMÚ API since 3.0.0.*

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs) 

# Aladin online (Czech Republic)

Home Assistant custom component for Aladin in the Czech Republic.

Data source: https://aladinonline.androworks.org/

## Installation

### HACS

1. Add [repository](https://github.com/kukulich/home-assistant-aladin-online/) as "Custom repository" in "Integrations" menu in [HACS](https://hacs.xyz/) (Home Assistant Community Store)  
   <small>*HACS is a third party community store and is not included in Home Assistant out of the box.*</small>
2. Install the integration in HACS
3. Restart Home Assistant
4. Integration should be available in the integrations UI

### Manual

1. [Download integration](https://github.com/kukulich/home-assistant-aladin-online/)
2. Copy the folder `custom_components/aladin-online` from the zip to your config directory
3. Restart Home Assistant
4. Integration should be available in the integrations UI
