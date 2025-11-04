# Opskrifts App

Et simpelt Windows-program til at administrere madopskrifter.

## Hvad kan programmet?

- Opret nye opskrifter (forretter, hovedretter og desserter)
- Gem opskrifter lokalt på din computer
- Se alle dine gemte opskrifter
- Tilføj ingredienser og fremgangsmåde til hver opskrift

## Sådan bruges programmet

1. Åbn projektet i Visual Studio
2. Tryk F5 for at køre programmet
3. Brug formularen til at oprette og gemme opskrifter

## Teknisk information

- **Platform:** Windows Desktop
- **Framework:** .NET 8.0
- **Type:** Windows Forms Application
- **Datalagring:** JSON fil (fileOpskrifter.json)

## Projektstruktur

- `Opskrift/` - Forskellige opskriftstyper (Forret, Hovedret, Dessert)
- `Factories/` - Fabriksklasser til at oprette opskrifter
- `JSON/` - Læs og skriv opskrifter til fil

## Eksamensprojekt

Dette projekt blev udviklet som eksamensopgave i *Videregående programmering* for at demonstrere objektorienteret design og Factory pattern.
