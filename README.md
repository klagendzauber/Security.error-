# Anti-Nuke Bot – GitHub Pages Seiten

Dieses Paket enthält die öffentlichen Seiten für Discords Felder „Terms of Service URL“ und „Privacy Policy URL“.

## Vor dem Veröffentlichen

Öffne `terms.html` und `privacy.html` und ersetze **alle gelb markierten Platzhalter**:

- vollständiger Name oder Organisation, die den Bot betreibt
- Kontakt-E-Mail, unter der Datenschutzanfragen wirklich beantwortet werden
- Postanschrift, soweit sie für dein Angebot erforderlich ist
- Hosting-Anbieter und Serverstandort/-region, auf dem Bot und Dashboard laufen
- prüfe die tatsächliche Datenverarbeitung und ob Rechtsgrundlage, Löschfristen und Host-Angaben zu deinem Einsatz passen

Lade keine Identitätsdokumente, Bot-Tokens, `.env`-Dateien, Datenbanken oder Serverkonfigurationen in dieses Repo hoch. GitHub Pages veröffentlicht die Website öffentlich.

## GitHub Pages aktivieren

1. Erstelle auf GitHub ein **neues öffentliches Repository nur für diese Seiten**, z. B. `anti-nuke-policy`.
2. Lade `index.html`, `terms.html`, `privacy.html` und `style.css` in den Hauptordner (`main`-Branch) hoch.
3. Öffne **Settings → Pages**.
4. Wähle unter **Build and deployment**: **Deploy from a branch**, dann Branch `main` und Ordner `/(root)`, anschließend **Save**.
5. Warte, bis GitHub die Seite veröffentlicht hat. Die Adressen lauten dann etwa:
   - `https://DEIN-GITHUB-NAME.github.io/anti-nuke-policy/terms.html`
   - `https://DEIN-GITHUB-NAME.github.io/anti-nuke-policy/privacy.html`
6. Öffne beide URLs in einem privaten Browserfenster und kontrolliere, dass sie laden und keine Platzhalter mehr enthalten.
7. Trage die jeweilige URL im Discord Developer Portal beim Bot unter **App Verification** ein. Danach die Checkliste neu laden.

Die Dateinamen und Beispiel-URLs kannst du ändern; dann müssen die Links im Index sowie die URLs im Discord Portal entsprechend angepasst werden.

## Hinweis

Die Texte sind ein auf den derzeitigen Projektcode zugeschnittener Ausgangsentwurf und keine anwaltliche Prüfung. Insbesondere Anbieter-/Impressumsangaben, der Hosting-Anbieter, die konkrete Rechtsgrundlage und der tatsächliche Betrieb müssen vom Betreiber geprüft und ergänzt werden. Discord verlangt eine öffentliche Datenschutzerklärung, die klar beschreibt, welche Daten verarbeitet werden, wie sie genutzt werden und wie Löschanfragen gestellt werden können.
