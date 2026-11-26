# Datele proiectului

Completați această fișă înainte de a pune fișierul CSV în acest folder. Fișierele rămân sub 5 MB; dacă setul original este mai mare, se decupează (coloanele și anii de interes) și se explică aici cum.

| Câmp | Valoare |
| --- | --- |
| Fișier | date.csv |
| Sursa (instituție, pagină) | Meteostat (Stația meteorologică Baia Mare), https://meteostat.net |
| Data descărcării | 26.11.2026 |
| Licența datelor | CC BY-NC 4.0 / Licență deschisă Meteostat |
| Cum a fost obținut fișierul | Export CSV (date orare) din interfața web Meteostat pentru stația Baia Mare |
| Prelucrări făcute înainte de commit | Niciuna (fișier brut descărcat) |

## Coloane

| Coloană | Tip | Semnificație | Unitate |
| --- | --- | --- | --- |
| `time` | dată și oră (`YYYY-MM-DD HH:MM:SS`)| Data și ora înregistrării | - |
| `temp` | real | Temperatura aerului | °C |
| `dwpt` | real | Punctul de rouă (dew point) | °C |
| `rhum` | întreg/real | Umiditatea relativă a aerului | % |
| `prpc` | real | Cantitate de precipitații | mm |
| `snow` | întreg/real | Grosimea stratului de zăpadă | mm |
| `wdir` | întreg | Direcția vântului | ° (grade) |
| `wspd` | real | Viteza medie a vântului | km/h |
| `wpgt` | real | Rafala maximă de vânt (peak wind gust) | km/h |
| `pres` | real | Presiunea atmosferică la nivelul mării | hPa |
| `tsun` | întreg | Durata de strălucire a soarelui | minute |
| `coco` | întreg | Codul stării vremii (weather condition code) | - |

## Citare în raport

Intrarea BibTeX corespunzătoare din `report/refs.bib`: `meteostat2026`.

## Date personale

Fișierele din acest folder nu conțin date personale (nume, adrese, identificatori) ale unor persoane fizice.
