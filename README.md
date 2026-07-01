# Rome Reis

Deze repository bevat de LaTeX-bronnen en gegenereerde PDF-bestanden voor een Rome-reisboekje en bijbehorende formele Italiaanse brieven.

## Inhoud

- `reisgids_rome_a5.tex` — A5 reisgids Rome
- `lettera_richiesta_ingressi_roma.tex` — Italiaanse brief in Broekhin-stijl
- `lettera_roercollege_richiesta_ingressi_roma.tex` — Italiaanse brief in ROER College-stijl
- `lettera_sint_ursula_richiesta_ingressi_roma.tex` — Italiaanse brief in Sint Ursula-stijl
- `logo.png` — Broekhin-logo
- `kaartjeRome.jpg` — Rome-kaartje voor het titelblad
- `ROER.png` — ROER-logo
- `SU.png` — Sint Ursula-logo
- PDF-bestanden met de gegenereerde output

## Compilatie

Je hebt MiKTeX of een andere LaTeX-distributie nodig.

Open een terminal in deze map en voer uit:

```powershell
pdflatex -interaction=nonstopmode reisgids_rome_a5.tex
pdflatex -interaction=nonstopmode lettera_richiesta_ingressi_roma.tex
pdflatex -interaction=nonstopmode lettera_roercollege_richiesta_ingressi_roma.tex
pdflatex -interaction=nonstopmode lettera_sint_ursula_richiesta_ingressi_roma.tex
```

## Opmerkingen

- De PDF's zijn al gegenereerd en toegevoegd aan deze repository.
- Houd `.aux`, `.log` en andere tijdelijke LaTeX-bestanden uit de repo met behulp van `.gitignore`.
