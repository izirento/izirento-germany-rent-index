# Germany: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Germany: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- EU rent price change for all 27 member states: [izirento-eu-rent-index](https://github.com/izirento/izirento-eu-rent-index)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

Rules that depend on region or municipality (for example designated tight-market areas) are described at national level only.

## IziRento pages for this country

- [Home, Deutsch](https://izirento.com/de-de)

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Civil Code (BGB), tenancy chapter, §§ 535 ff. Residential rent rules including deposit, rent increases and termination are in the BGB. | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__551.html) |
| deposit | Maximum deposit | Security may not exceed three times the monthly rent, excluding service charges paid as a flat rate or advance (§ 551(1) BGB). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__551.html) |
| deposit | Deposit handling | Landlord must invest a cash deposit with a bank at the rate usual for savings deposits with three months notice, separate from the landlord's own assets; the tenant may pay in three equal monthly instalments (§ 551(2)-(3) BGB). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__551.html) |
| rent_increase | Increase to local comparative rent | Landlord may ask for consent to a rise up to the local comparative rent if the rent has been unchanged for 15 months; the request may be made at the earliest one year after the last increase (§ 558(1) BGB). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__558.html) |
| rent_increase | Cap on increases | Rent may not rise by more than 20 percent within three years (15 percent in areas designated by Land governments as having endangered housing supply), excluding modernisation and service-charge changes (§ 558(3) BGB). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__558.html) |
| rent_control | Rent at start of tenancy in tight markets | In areas with a tight housing market designated by a Land ordinance, rent at the start of a tenancy may exceed the local comparative rent by at most 10 percent (§ 556d(1) BGB). Designations are made by each Land, so they differ by municipality. | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__556d.html) |
| termination | Landlord termination: ground and notice | Landlord may terminate only with a legitimate interest (e.g. tenant breach, own use) and not to raise rent (§ 573 BGB). Notice is three months, extended by three months after five and again after eight years of tenancy (§ 573c BGB). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/bgb/__573.html) |
| energy_certificate | Energy performance certificate on letting | An energy certificate must be issued when a building or dwelling is let, unless a valid one already exists (§ 80(3) of the Building Energy Act; the official page shows the act under the title Gebäudemodernisierungsgesetz - GModG). | [Federal Ministry of Justice / juris](https://www.gesetze-im-internet.de/geg/__80.html) |
| landlord_registration | National landlord register or licence | (empty) | - |
| rent_level_change | Rent price change, 2025 annual average (HICP actual rentals for housing) | 2.1 percent (2024: 2.2 percent) | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_aind?format=JSON&lang=EN&coicop=CP041&unit=RCH_A_AVG&geo=DE&time=2025) |
| rent_level_change | Rent price change, December 2025 year on year (HICP actual rentals for housing) | 2.2 percent | [Eurostat](https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/data/prc_hicp_manr?format=JSON&lang=EN&coicop=CP041&unit=RCH_A&geo=DE&time=2025-12) |

## Deutsch

**Deutschland.** Offene Daten zu Miete und Pflichten von Vermietern: Kaution, Mieterhöhung, Kündigungsfristen und Mietvertrag, zu jedem Wert mit Link zur amtlichen Quelle.

*Die Daten werden wie besehen und ohne jegliche Haftung bereitgestellt. Wir ordnen lediglich, was amtliche Quellen veröffentlichen. Gesetze ändern sich: Bitte prüfen Sie jeden Wert anhand der verlinkten Primärquelle.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `germany_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |
| (Eurostat rows) | The last rows of the CSV hold the Eurostat rent price change for this country (HICP actual rentals, item CP041) |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Rent price change is the Eurostat HICP index of rents actually paid. It shows how rents moved, not what they cost. The API responses used were last updated by Eurostat on 6 February 2026, so the latest period is December 2025.
4. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Germany: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-germany-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
