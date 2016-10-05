RStudio installeren als administrator
================

De installatiebestanden voor de stabiele versies zijn beschikbaar via <http://www.rstudio.com/products/rstudio/download/>. De preview versie is beschikbaar via <https://www.rstudio.com/products/rstudio/download/preview/>

Windows
-------

### Nieuwe installatie en upgrade van RStudio

RStudio upgraden doe je door de nieuwe versie te installeren over de oude.

1.  Zorg dat eerst `R` geïnstalleerd is.
2.  Voer het 64-bit installatiebestand uit.
3.  Welkom bij de installatie: klik op *volgende*.
4.  Geef aan dat je `RStudio` wilt installeren in `C:\R\Rstudio` en klik op *volgende*.
5.  Klik op *installeren*.
6.  Klik op *voltooien*.

**RStudio mag niet met admininstratorrechten gestart worden.** Anders worden een aantal R packages met administrator rechten geïnstalleerd waardoor de gebruiker ze niet meer kan updaten.

Test de configuratie door RStudio te starten als een ***gewone*** gebruiker.

### Afwijkingen t.o.v. default installatie

-   Installeren naar `C:\R\RStudio` i.p.v. `C:\Program Files\R\RStudio`
