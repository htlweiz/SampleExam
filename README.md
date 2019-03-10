# SampleExam

In dieser Aufgabe sollen Sie die Verwendung von Github Education kennenlernen indem Sie ein einfaches Programm fuer den Arduino erstellen und hier abgeben.

Als Programm duerfen Sie das Blink-Beispielprogramm aus der Arduino Software verwenden und umbenennen.

Lernziele:
  * Annehmen einer Github-Education Aufgabe.
  * clonen eines remote Repositories zu einer lokalen Kopie.
  * Bearbeitung der Aufgabe auf dem lokalem Laufwerk.
  * "pushen" der Lokalen Aenderungen auf das remote Repository

## Ein Beispielhafter Ablauf der Abgabe

Verwenden Sie fuer diesen Arbeitsablauf die GIT-Bash ...

```bash
# Klonen Sie die Aufgabe auf Ihren lokalen Rechner.

https_proxy=http://proxy:3128 git clone https://die.adresse/zu/ihrem/persoenlichem/aufgaben/repository

# Erstellen Sie in dem frisch ausgechecktem Repository ein Blinklicht 
# Programm fuer den Arduino names TestBlink. Fuegen Sie das Programm zu
# Ihrem Repository hinzu:

git add TestBlink/TestBlink.ino

# ueberpruefen Sie den Status Ihres Repository

git status

# wenn alles in Ordnung ist, commiten Sie die Aenderungen

git commit -m "Aufgabe erfuellt"

# und pushen Sie Ihre Aenderungen auf das Remote Repository umd die
# Abgabe der Aufgabe abzuschliessen

https_proxy=http://proxy:3128 git push
```

Viel Erfolg.
