# Game Launcher

Toate jocurile de pe PC într-un singur loc: Steam, GOG, Epic, Xbox și cele din folderele tale.
Un launcher pentru Windows, făcut ca lucrare de licență și dat câtorva prieteni.

[![Descarcă GameLauncher-Setup.exe](https://img.shields.io/github/v/release/GreenYRO/game-launcher-releases?label=Descarc%C4%83%20GameLauncher-Setup.exe&style=for-the-badge&color=2ea44f)](https://github.com/GreenYRO/game-launcher-releases/releases/latest/download/GameLauncher-Setup.exe)
[![Descărcări](https://img.shields.io/github/downloads/GreenYRO/game-launcher-releases/total?style=for-the-badge&label=desc%C4%83rc%C4%83ri)](https://github.com/GreenYRO/game-launcher-releases/releases)

<!-- Capturile vin aici când există: docs/media/grid.png (grila), docs/media/game-page.png, docs/media/tv-mode.png
<p align="center">
  <img src="docs/media/grid.png" alt="Grila de coperți" width="820">
</p>
-->

**[English below ↓](#english)**

## Descarcă și instalează

1. Descarcă **[GameLauncher-Setup.exe](https://github.com/GreenYRO/game-launcher-releases/releases/latest/download/GameLauncher-Setup.exe)**
   (aprox. 70 MB). Linkul duce mereu la ultima versiune; lista completă e la
   [Releases](https://github.com/GreenYRO/game-launcher-releases/releases). Merge pe Windows 11 sau 10, pe 64 de biți.
2. Rulează-l. Nu cere parolă de administrator și pune scurtături pe Desktop și în meniul Start.
3. **Windows o să te avertizeze**: „Windows a protejat PC-ul” (*Windows protected your PC*). Apasă pe
   **Mai multe informații** (*More info*), apoi pe **Rulează oricum** (*Run anyway*). Avertismentul apare
   pentru că fișierul nu e semnat digital de o firmă (o astfel de semnătură costă bani în fiecare an), nu
   pentru că programul ar avea ceva. Rulează-l doar dacă l-ai luat de pe pagina asta sau direct de la mine.
4. La prima pornire te întreabă unde îți ții jocurile și, opțional, o cheie SteamGridDB pentru mai multe
   coperți. Poți sări peste a doua întrebare.

<!-- docs/media/smartscreen.png: captura cu „Mai multe informații” / „Rulează oricum”
<p align="center">
  <img src="docs/media/smartscreen.png" alt="Avertismentul Windows SmartScreen" width="520">
</p>
-->

## Ce face

- Găsește jocurile instalate din **Steam, GOG, Epic și Xbox** și pe cele pe care le-ai pus singur
  într-un folder (copiate, dezarhivate sau instalate cu installer-ul lor).
- Le arată ca o **grilă de coperți**. Fiecare joc are pagina lui: descriere, capturi, știri și prețul din Steam.
- Le **pornește** și ține minte **cât ai jucat** la cele pornite din el; pentru jocurile din Steam arată
  timpul pe care îl ține Steam.
- Face **copii ale salvărilor** jocurilor pornite din el.
- Favorite, statistici și o pagină cu spațiul ocupat de jocuri pe fiecare disc.
- Merge cu **controlerul** (Xbox, DualSense) și pe **televizor**, în modul TV.

## Ce citește de pe PC-ul tău

- **Folderele cu jocuri pe care le alegi tu.** Le schimbi oricând din Settings → Finding games → Game folders.
- **Ce au instalat Steam, GOG, Epic și Xbox**, din fișierele lor de pe PC.
- **Timpul jucat pe care Steam îl ține singur**, pentru fiecare cont care a intrat pe PC. Tu alegi în
  Settings care conturi sunt ale tale.
- **Numele și datele fișierelor din folderele de salvări** (Documente, AppData), ca să afle unde își ține
  salvările un joc pornit din launcher. Nu le deschide și nu le citește conținutul.

## Ce nu face niciodată

- **Nu are cont și nu cere niciun login.**
- **Nu trimite nimic despre tine nicăieri.** Tot ce știe rămâne pe PC-ul tău.
- De pe internet cere doar **pagini publice ale magazinului Steam** (coperți, descrieri, prețuri, știri)
  și, o dată pe zi, întreabă **GitHub** dacă a apărut o versiune nouă a launcher-ului. Nu trimite nume, cont
  sau altceva despre tine. Poți opri tot: Settings → „Allow network lookups”.
- **SteamGridDB** (mai multe coperți) se folosește doar dacă îți pui singur o cheie gratuită a ta: pe
  steamgriddb.com intri cu contul Steam, Preferences → API, generezi cheia și o lipești la prima pornire sau
  oricând în Settings → Artwork and the internet.

## Actualizare

Launcher-ul îți spune singur când a apărut o versiune nouă: un mesaj la pornire și, în Settings → About →
Updates, butonul **Open the download page**. Nu descarcă și nu instalează nimic singur. Închizi launcher-ul
și rulezi noul `GameLauncher-Setup.exe` peste cel vechi. Păstrează tot: jocurile, timpul jucat, coperțile
alese și setările.

## Dacă ceva nu merge

Settings → Your library data → **Save diagnostics...** face un zip pe care mi-l trimiți. Conține jurnalul
programului, versiunea, setările (fără cheia SteamGridDB) și ce a găsit ultima căutare de jocuri, cu căile
folderelor, ca să-mi dau seama de ce nu găsește un joc. **Nu conține** timpul jucat, notițele, ce ai plătit
pe jocuri sau conturile tale Steam.

## Unde îi stau datele

Într-un singur folder: **`%LOCALAPPDATA%\Programs\Game Launcher`** (scrie asta în bara de adrese din File
Explorer). Acolo sunt setările, biblioteca, copiile de siguranță și copiile salvărilor. Copiezi folderul și
ai o copie de rezervă.

## Pentru lucrarea mea de licență

Launcher-ul este lucrarea mea de licență. S-ar putea să te rog să-mi trimiți un **export anonim** al
bibliotecii tale: ce jocuri ai și cât le-ai jucat, fără căi de foldere și fără nume de conturi, ca să pot
compara mai multe biblioteci în lucrare. **E alegerea ta.** Dacă nu vrei, nu se trimite nimic, iar
launcher-ul merge exact la fel.

Dacă vrei: Settings → Your library data → **Anonymous export...**. Fereastra îți arată dinainte ce conține,
cu numerele bibliotecii tale; salvezi un fișier pe care îl poți deschide în Notepad și citi tot. Din
launcher nu pleacă nimic singur: fișierul mi-l trimiți tu. Ce ai plătit pe jocuri intră doar dacă bifezi
asta; conturile Steam apar ca „A”, „B”, fără nume sau numere.

## Dezinstalare

Setări Windows → Aplicații → Game Launcher → Dezinstalare. Te întreabă dacă vrei să păstrezi setările și
timpul jucat, ca să le regăsești dacă îl instalezi din nou.

## Codul

Codul nu e în acest depozit; aici sunt doar installerele.

---

## English

All the games on your PC in one place: Steam, GOG, Epic, Xbox and the ones in your own folders.
A Windows game launcher made for a bachelor thesis and shared with a few friends.

### Download and install

1. Download **[GameLauncher-Setup.exe](https://github.com/GreenYRO/game-launcher-releases/releases/latest/download/GameLauncher-Setup.exe)**
   (about 70 MB). The link always points at the newest version; every version is listed under
   [Releases](https://github.com/GreenYRO/game-launcher-releases/releases). Windows 11 or 10, 64-bit.
2. Run it. It needs no administrator password and adds shortcuts to the Desktop and the Start menu.
3. **Windows will warn you**: "Windows protected your PC". Click **More info**, then **Run anyway**. The
   warning appears because the file is not digitally signed by a company (such a signature costs money
   every year), not because anything is wrong with the program. Only run it if you got it from this page
   or directly from me.
4. On first run it asks where you keep your games and, optionally, for a SteamGridDB key for more cover
   art. You can skip the second question.

### What it does

- Finds the games installed through **Steam, GOG, Epic and Xbox** and the ones you put in a folder
  yourself (copied, unpacked or installed with their own installer).
- Shows them as a **grid of covers**. Each game has its own page: description, screenshots, news and the
  Steam price.
- **Launches** them and remembers **how long you played** the ones started from it; for Steam games it
  shows the time Steam itself keeps.
- **Backs up the saves** of games started from it.
- Favorites, stats and a page showing how much space games take on each drive.
- Works with a **controller** (Xbox, DualSense) and on a **TV**, in TV mode.

### What it reads on your PC

- **The game folders you choose.** Change them any time under Settings → Finding games → Game folders.
- **What Steam, GOG, Epic and Xbox have installed**, from their own files on the PC.
- **The playtime Steam keeps**, for every account that has signed in on the PC. You pick in Settings which
  accounts are yours.
- **File names and dates in the save folders** (Documents, AppData), to find where a game started from the
  launcher keeps its saves. It does not open or read their contents.

### What it never does

- **No account, no login.**
- **It sends nothing about you anywhere.** Everything it knows stays on your PC.
- From the internet it only fetches **public Steam store pages** (covers, descriptions, prices, news)
  and, once a day, asks **GitHub** whether a newer version of the launcher exists. No name, account or
  anything else about you is sent. You can turn all of it off: Settings → "Allow network lookups".
- **SteamGridDB** (more cover art) is used only if you add your own free key: sign in on steamgriddb.com
  with your Steam account, Preferences → API, generate a key and paste it on first run or any time under
  Settings → Artwork and the internet.

### Updating

The launcher tells you when a new version is out: a message at start-up and, under Settings → About →
Updates, the **Open the download page** button. It never downloads or installs anything on its own. Close
the launcher and run the new `GameLauncher-Setup.exe` over the old one. Everything is kept: games,
playtime, chosen covers and settings.

### If something goes wrong

Settings → Your library data → **Save diagnostics...** makes a zip you can send me: the program's log, the
version, the settings (without the SteamGridDB key) and what the last game search found, with folder
paths, so I can see why a game is missing. It **does not contain** playtime, notes, what you paid for games
or your Steam accounts.

### Where its data lives

In one folder: **`%LOCALAPPDATA%\Programs\Game Launcher`** (paste that into File Explorer's address bar).
Settings, the library, backups and save copies are all there. Copy the folder and you have a backup.

### For my bachelor thesis

The launcher is my bachelor thesis. I may ask you for an **anonymous export** of your library: which games
you have and how long you played them, with no folder paths and no account names, so I can compare several
libraries in the thesis. **It is your choice.** If you would rather not, nothing is sent and the launcher
works exactly the same.

If you want to: Settings → Your library data → **Anonymous export...**. The window shows beforehand what the
file will contain, with your library's numbers; you save a file you can open in Notepad and read in full.
Nothing leaves the launcher on its own: you send the file yourself. What you paid for games is included only
if you tick that box; Steam accounts appear as "A", "B", with no names or numbers.

### Uninstalling

Windows Settings → Apps → Game Launcher → Uninstall. It asks whether to keep your settings and playtime, so
you find them again if you reinstall.

### The code

The code is not in this repository; only the installers are.
