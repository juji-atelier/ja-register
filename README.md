# JA ESPORT — Team registration

Live page: https://juji-atelier.github.io/ja-register/

Team leaders fill in the team name, logo, players (in-game name, role, ID) and photos on their phone,
then send one file (`JA-TEAM-<team>.txt`) to the organiser on WhatsApp.
The organiser drops the files into **JA ESPORT CONSOLE → Schedule & Standings → Teams → 📥 Import team files**.

Nothing is uploaded anywhere: the page runs entirely in the phone's browser.

Link options (add to the URL):

- `?event=HQ%20CHAMPIONSHIP` – tournament name in the header
- `&wa=60123456789` – organiser's WhatsApp number (button to open the chat after sending)
- `&deadline=30%20Oct%2C%2010pm` – deadline shown under the title

## Tournament demo

`tournament.html` (https://juji-atelier.github.io/ja-register/tournament.html) is a Challonge-style demo for SUKSES V MLBB:
4 groups of 5 (round robin, BO1, 1 pt per win, tie-break points → head-to-head → kills → fewest deaths),
then an 8-team double-elimination bracket (group winners to the upper bracket, runners-up to the lower, BO3, Grand Final BO5),
plus captain result reporting and organiser approval. Demo data is saved in the browser only.

© JUJI-ATELIER SYSTEM
