## Proiect clima locală

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<utilizator>/<depozit>/blob/main/notebooks/analiza.ipynb)
[![Verificări depozit](../../actions/workflows/repo-check.yml/badge.svg)](../../actions/workflows/repo-check.yml)
[![Notebook reproductibil](../../actions/workflows/notebook-check.yml/badge.svg)](../../actions/workflows/notebook-check.yml)

Disciplina *Dezvoltare colaborativă și tehnologii cloud* (DCTC), Universitatea Tehnică din Cluj-Napoca, Centrul Universitar Nord din Baia Mare.

## Echipa sunshine

| Nume și prenume | Utilizator GitHub | Program | Rol inițial (s3-s6) | Rol 2 (s6-s10) | Rol 3 (s10-s14) |
| --- | --- | --- | --- | --- | --- |
| `<Belya Bianca>` | `<belyabianca9>` | MI / INF | coordonator | | |
| `<Belya Bianca>` | `<belyabianca9>` | MI / INF | responsabil depozit | | |
| Alexia Dirle | AlexiaDirle21 | MI / INF | responsabil raport | | |
| `<Darolti Larisa>` | `<laridarolti>` | MI / INF | responsabil date și notebook | | |

Proiectul nostru are ca temă studiul climei locale, concentrându-se pe analiza evoluției temperaturilor și a precipitațiilor din regiunea noastră în ultimii ani.

**Tema nr. `<3>`: `<clima locală>`**

Întrebarea studiului: `<Cum au evoluat temperaturile medii și precipitațiile în regiunea noastră în ultimii 10 ani?>`

Sursa datelor: vedeți [`data/README.md`](data/README.md).

## Cum se rulează

1. Deschideți notebook-ul cu butonul *Open in Colab* de mai sus (sau [`notebooks/analiza.ipynb`](notebooks/analiza.ipynb)).
2. *Runtime > Run all*. Notebook-ul citește datele direct din acest depozit (URL raw), nu are nevoie de fișiere locale.
3. Figurile se salvează în [`report/figures/`](report/figures/) și se folosesc în raport.

## Livrabile

| Livrabil | Unde se găsește | Termen |
| --- | --- | --- |
| T3 depozitul cu pull request-uri revizuite | acest depozit, [`docs/plan.md`](docs/plan.md) | s8 |
| T4 raportul (schelet, Introducere, bibliografie) | [`report/raport.pdf`](report/raport.pdf), [`report/refs.bib`](report/refs.bib), Overleaf: `<link de vizualizare>` | s10 |
| T5 notebook-ul reproductibil | [`notebooks/analiza.ipynb`](notebooks/analiza.ipynb) | s12 |
| T6 pagina proiectului | `<https://utilizator.github.io/depozit/>` | s12 |
| Versiunea finală | eticheta `v1.0` și release-ul ei, în *Releases* | s13 |

## Reguli de lucru

Sunt în [`CONTRIBUTING.md`](CONTRIBUTING.md): ramuri `feature/utilizator-scop`, pull request cu revizuire, mesaje de commit clare, un singur editor pentru `notebooks/analiza.ipynb`.

## Declarație privind utilizarea instrumentelor AI

`Nu am folosit instrumente AI.`

## Licență

Codul și textul echipei: [MIT](LICENSE). Datele au licența menționată în `data/README.md`.
