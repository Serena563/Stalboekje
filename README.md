# Stalboekje

Een eenvoudige fok-app voor Horse Nation, gemaakt om makkelijk te gebruiken.

## Wat zit erin
- **🐴 Mijn paarden**: je paarden in groepen (Merries, Hengsten, Veulens; zelf groepen toevoegen kan ook). Per paard: naam, S/D/G, vader, moeder en een notitie. Je kunt per paard ook de stamboom bekijken.
- **💞 Dekken**: kies een merrie en je ziet de dekhengsten. Bovenaan staan de hengsten zonder inteelt, de hoogste SDG eerst. Per hengst zie je de inteelt, of hij familie is en hoe hoog het veulen minstens ongeveer wordt.
- **🤰 Drachtig**: de drachtige merries met het aantal dagen tot de bevalling (7 dagen dracht). Met **🎉 Bevallen** voeg je het veulen meteen toe, met vader en moeder ingevuld.
- **📋 Plakken**: plak de pagina Mijn stal uit Horse Nation. Nieuwe paarden komen erbij (in dezelfde groepen als in het spel), bestaande worden bijgewerkt: S/D/G, trainingsniveaus en drachtig. Paarden die er niet meer in staan kun je in één keer weghalen. Plak je de stamboom van een paard, dan worden vader, moeder en grootouders bewaard voor de inteelt.
- **Fokbonus**: bij elk paard zie je ✅ Fokbonus, Fokbonus deels (met de percentages) of ⏳ Nog geen fokbonus, en wat er nog getraind moet worden voor de volle bonus. Bij Drachtig staat wat de merrie vóór de bevalling nog moet halen. Onder ℹ️ Wat is de fokbonus? staat de uitleg.
- **💾 Back-up**: lees het back-upbestand (.json) van de Horse Nation Stalmanager in voor de dekhengsten en stambomen, en maak je eigen back-up.

## Dropbox
- Bij 💾 Back-up staat **Verbinden met Dropbox**. Je logt in met je eigen Dropbox; daarna gaat elke wijziging vanzelf naar het bestand `stalboekje.json` in je Dropbox.
- Doe dit op elk apparaat. Een nieuw apparaat haalt de paarden dan uit Dropbox.
- Is er op twee apparaten tegelijk iets veranderd, dan vraagt de app welke versie je wilt houden.
- Voor de beheerder: zet het adres van deze app (bijv. `https://serena563.github.io/naam-van-de-repo/`) bij **Redirect URIs** in de Dropbox App Console, bij dezelfde app als de Stalmanager.

## Goed om te weten
- Alles wordt bewaard in de browser op het apparaat waarop je de app gebruikt.
- Inteelt wordt berekend over 4 generaties, net als in Horse Nation.
- De app toont standaard alleen Friese dekhengsten. Andere rassen zet je aan bij Back-up → Rassen.

## Op GitHub Pages zetten
Zet `index.html` en `README.md` in een nieuwe repository en zet bij Settings → Pages de branch `main` aan.
