# Plasma Addon Engine

> 🕒 **Status: concept / future project — development has not started.**
>
> 🕒 **Status: pomysł na przyszłość — prace nad silnikiem nie zostały rozpoczęte.**

[Polski](#-polski) · [English](#-english)

---

## 🇵🇱 Polski

### O projekcie

**Plasma Addon Engine** to pomysł na niezależny silnik zarządzania aktualizacjami dodatków dla **KDE Plasma 6**.

Repozytorium zostało utworzone **na przyszłość, jako plan awaryjny** na wypadek, gdyby projekt [`plasmoid-updater`](https://github.com/uwuclxdy/plasmoid-updater) przestał być rozwijany, utracił zgodność z nowymi wersjami KDE Plasma lub przestał działać i nie otrzymywał poprawek.

**Obecnie nie planuję zastępować działającego `plasmoid-updater`.** W projekcie [Plasma Addon Manager](https://github.com/wolfgangxxiii/bazzite-kde-installer-plasmoid-updater-gui) nadal korzystamy z oryginalnego narzędzia.

### Kiedy projekt może zostać uruchomiony?

- Gdy autor `plasmoid-updater` zakończy jego utrzymywanie.
- Gdy zmiany w KDE Plasma lub KDE Store uniemożliwią dalsze korzystanie z narzędzia.
- Gdy pojawią się istotne, nierozwiązane problemy z bezpieczeństwem, kompatybilnością lub aktualizacjami.

### Wstępna koncepcja

Jeśli projekt będzie potrzebny, celem stanie się niezależny silnik, potencjalnie napisany w **Rust**, z funkcjami takimi jak:

- wykrywanie zainstalowanych dodatków KDE Plasma;
- sprawdzanie aktualizacji przez KDE Store;
- bezpieczne instalowanie i weryfikowanie paczek;
- kopie zapasowe i przywracanie poprzednich wersji;
- obsługa automatyzacji i integracja z **Plasma Addon Manager**;
- współpraca z różnymi dystrybucjami Linuksa.

To **założenia**, a nie lista ukończonych funkcji.

### Aktualny stan

- **Brak działającego silnika i wydań.**
- **Nie należy instalować tego repozytorium jako zamiennika `plasmoid-updater`.**
- Dalszy rozwój zostanie rozważony dopiero wtedy, gdy będzie uzasadniony.

---

## 🇬🇧 English

### About the project

**Plasma Addon Engine** is an idea for an independent update engine for **KDE Plasma 6** add-ons.

This repository is being kept **for the future as a contingency plan** in case [`plasmoid-updater`](https://github.com/uwuclxdy/plasmoid-updater) is no longer maintained, becomes incompatible with newer KDE Plasma versions, or stops working without receiving fixes.

**There are currently no plans to replace a working `plasmoid-updater`.** [Plasma Addon Manager](https://github.com/wolfgangxxiii/bazzite-kde-installer-plasmoid-updater-gui) continues to use the original tool.

### When might development begin?

- If the maintainer of `plasmoid-updater` ends support.
- If changes to KDE Plasma or KDE Store break its functionality.
- If important security, compatibility, or update-related issues remain unresolved.

### Preliminary concept

If a replacement becomes necessary, the goal would be an independent engine, potentially written in **Rust**, with capabilities such as:

- discovering installed KDE Plasma add-ons;
- checking KDE Store for updates;
- safely installing and verifying packages;
- creating backups and rolling back failed updates;
- supporting background automation and **Plasma Addon Manager** integration;
- working across Linux distributions.

These are **proposed goals, not implemented features**.

### Current status

- **No functional engine or releases are available.**
- **Do not install this repository as a replacement for `plasmoid-updater`.**
- Development will be reconsidered only if there is a practical need.

---

## Credits / Podziękowania

The existing [`plasmoid-updater` project by uwuclxdy](https://github.com/uwuclxdy/plasmoid-updater) is the inspiration for this contingency plan.

**Plasma Addon Engine is not an official KDE project and is not affiliated with the original maintainer.** If any upstream source code is reused in the future, its authorship and license requirements will be preserved.

## License / Licencja

This repository currently contains a [GNU GPLv3 license](LICENSE). Any future implementation will document the applicable licensing and third-party attributions.
