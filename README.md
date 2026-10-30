# Talas Tools

Talas Tools je paket alata za montažu koji pravi Talas Akademija. Radi u Adobe Premiere Pro-u i u DaVinci Resolve-u, na Mac-u i na Windows-u. Ceo interfejs je na srpskom.

Ovde se nalaze samo instalacije. Svaka nova verzija izlazi kao poseban release, pa uvek možeš da preuzmeš najnoviju ili da se vratiš na neku stariju.

## Šta dobijaš

### AutoCutter

AutoCutter sam seče tišine iz dijaloga. Izabereš celu sekvencu, deo između In i Out tačaka ili selektovane klipove, podesiš prag šuma i tempo, i pogledaš pregled pre nego što bilo šta iseče. Tišine možeš da ukloniš, utišaš ili da ih izbaciš a da praznine ostanu na timeline-u. Na svaki rez može da ide kratak Constant Power crossfade, da se ne čuju klikovi. Pre rezanja AutoCutter napravi sigurnosnu kopiju sekvence, tako da original ostaje netaknut. Podešavanja koja ti odgovaraju sačuvaš kao preset.

### Preuzimanje videa

Ovaj alat skida video sa YouTube-a, TikTok-a ili X-a i odmah ga ubacuje u projekat. Samo nalepiš link i izabereš kvalitet. Za 1080p dobijaš H.264 mp4 koji radi bez konverzije.

### Paste It

Paste It stavlja sliku iz clipboarda pravo na timeline. Kopiraš screenshot ili sliku iz browsera, klikneš Nalepi, i slika ide na prvi slobodan video trag, tačno na poziciju playheada.

### Quick Apply (samo Premiere Pro)

Quick Apply radi na prečicu koju sam podesiš. Pritisneš je bilo gde u Premiere-u, ukucaš ime efekta ili preseta i on se primeni na izabrane klipove.

| Alat | Premiere Pro | DaVinci Resolve |
|---|:---:|:---:|
| AutoCutter | da | da |
| Preuzimanje videa | da | da |
| Paste It | da | da |
| Quick Apply | da | ne |

Kad prvi put otvoriš panel, kratak vodič ti pokaže gde je šta. Možeš ga preskočiti i kasnije ponovo pokrenuti.

## Ko može da ga koristi

Talas Tools je za članove [Talas Akademije na Skool-u](https://www.skool.com/talas-akademija) koji su u zajednici duže od 90 dana. Prijavljuješ se mejlom koji koristiš na Skool-u: upišeš ga, stigne ti šestocifreni kod, ukucaš ga i to je to. Ako kod ne stigne, prvo pogledaj spam. Ako ga nema ni tamo, taj mejl verovatno još nema pristup.

Jedan nalog radi na jednom računaru u isto vreme. Ako se prijaviš na drugom računaru, panel te pita da li da odjavi onaj prvi.

## Šta ti treba

- Adobe Premiere Pro 2023 ili noviji, ili DaVinci Resolve (besplatna verzija i Studio)
- macOS ili Windows

Ništa drugo ne moraš da instaliraš. Sve što alatima treba već je u instalaciji.

## Preuzimanje

Otvori stranicu sa [najnovijom verzijom](https://github.com/luka-jaksic/talas-tools/releases/latest) i u delu Assets preuzmi fajl za svoj program i sistem:

| Program | Mac | Windows |
|---|---|---|
| Premiere Pro | `TalasTools-Premiere-<verzija>.dmg` | `TalasTools-Premiere-<verzija>-setup.exe` |
| DaVinci Resolve | `TalasTools-Resolve-<verzija>.dmg` | `TalasTools-Resolve-<verzija>-setup.exe` |

Starije verzije su na stranici [Releases](https://github.com/luka-jaksic/talas-tools/releases).

## Instalacija na Mac-u

1. Zatvori Premiere Pro ili DaVinci Resolve.
2. Otvori preuzeti `.dmg` i dvaput klikni na `Install Talas Tools ... .pkg`.
3. Mac će verovatno reći da ne može da proveri ko je napravio paket. To je zato što instalacija još nije potpisana Apple sertifikatom. Klikni Done (ili OK), pa otvori System Settings › Privacy & Security. Pri dnu stoji poruka o Talas Tools paketu. Klikni Open Anyway, upiši lozinku i ponovo pokreni paket.
4. Prođi kroz instalaciju do kraja.

## Instalacija na Windows-u

1. Zatvori Premiere Pro ili DaVinci Resolve.
2. Pokreni preuzeti `-setup.exe`.
3. Ako Windows prikaže plavi prozor "Windows protected your PC", klikni More info, pa Run anyway. Pojavljuje se iz istog razloga kao na Mac-u: instalacija još nema sertifikat.
4. Prođi kroz instalaciju do kraja.

## Kako se otvara

**Premiere Pro:** pokreni Premiere i otvori Window › Extensions › Talas Tools. Panel možeš da zakačiš gde god ti odgovara u workspace-u.

**DaVinci Resolve:** pokreni Resolve, otvori projekat, pa Workspace › Scripts › Talas Tools. Otvoriće se Talas Tools prozor povezan sa Resolve-om. Ako piše da nije povezano, ponovo klikni Workspace › Scripts › Talas Tools.

Prvi put ćeš morati da se prijaviš (vidi gore), posle toga ostaješ prijavljen.

## Nova verzija

Preuzmi novu instalaciju sa [Releases](https://github.com/luka-jaksic/talas-tools/releases/latest) i instaliraj je preko stare, isto kao prvi put. Ne moraš ništa prethodno da brišeš. Presetovi i podešavanja ostaju.

## Deinstalacija

**Mac:** u `.dmg` fajlu i u Applications › Utilities nalazi se Uninstall Talas Tools. Pokreni ga.

**Windows:** Settings › Apps › Installed apps, nađi Talas Tools i klikni Uninstall.

## Greške i predlozi

Na početnom ekranu panela je dugme Prijavi grešku / Pošalji feedback. Otvara kratku formu. Napiši šta si radio i šta se desilo, a ako možeš, dodaj i screenshot.
