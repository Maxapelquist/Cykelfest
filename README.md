# Cykelfest

# Viktigt för att köra koden (kortfattat).
- Att filformatet är av typ xlsx

- Att formatet följer "CykefiEzten 2021(Svar).xlsx"

- Att byta ut filnamnet till filen som ska köras. Detta görs på första raden i main funktionen.



# Viktigt för att köra koden (utförligt):
-Att namnet på kolumnen för telefonnummer är "Telefonnummer till den ni ska vara hos (07x-xxxxxxx)". När programmet tar bort dubletter hämtas information utifrån exakt det kolumnnamnet.

-Att kolumnerna kommer i samma ordning som i "CykefiEzten 2021(Svar).xlsx". På flertalet ställen i koden hämtas information utifrån nr på kolumner. 

-Om efterätterna ska hamna på området för Tvistevägen/Ålidhöjd krävs det att området heter "Tvistevägen/Ålidhöjd". Programmet portionerar ut efter exakt den stringen

- Om grupperingen ska gå ihop måste antalet lag/grupper vara 9st eller 15+3*n st. Detta gäller inte bara för denna kod, utan det är omöjligt att få ihop det annars. Om grupperingen inte gåt ihop kommer (1 eller 2 st) lag plockas exkluderas. Om så sker kommer en varningstext visas som beskriver hur många grupper som är exkluderade (1 eller 2 st), samt vilka grupper det är. Dessa grupper måste då alltså handpåläggas i efterhand.

-Att det inte är några missing values i kolumnerna för land, namn, område, adress eller telefonnummer, isåfall kommer "nan" skrivas ut i word filerna.
Om det är två eller fler st missing values i kolumnen för telefonnummer kommer det klassificeras som en dubblett/dubletter. 1 st (eller fler) av lagen kommer då exkluderas utan varning.

Övrig notering: I wordfilerna skrivs namnet, telefonnummret och adressen till hosten ut. Namnet som skrivs ut är baserat på "Lagmedlem 1". Namnet behöver alltså inte nödvändigtvis matcha telefonnummret och adressen om gruppen har anmält med hostens namn som "Lagmedlem 2".


