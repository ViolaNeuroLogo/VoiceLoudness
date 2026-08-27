# VoiceTrainer Light

Eenvoudige webapp die de luidheid van je stem meet via de microfoon en toont
hoe die zich verhoudt tot je gemiddelde volume. Werkt volledig in de browser,
geen backend nodig.

## Gebruiken op je telefoon

Deze app gebruikt `getUserMedia` voor microfoontoegang. Mobiele browsers
staan dat alleen toe via **https** (of `localhost`) — niet via een lokaal
`file://` bestand of gewoon `http://`. Daarom is deze repo klaargezet voor
GitHub Pages, dat gratis https-hosting geeft.

### GitHub Pages inschakelen

1. Push deze repo naar GitHub.
2. Ga naar **Settings → Pages** in de repo.
3. Zet **Source** op de `main` branch, map `/ (root)`.
4. Na een minuutje is de app live op
   `https://<jouw-gebruikersnaam>.github.io/<repo-naam>/`.
5. Open die link op je telefoon en geef toegang tot de microfoon.
