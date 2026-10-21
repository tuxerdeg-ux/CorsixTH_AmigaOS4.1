# CorsixTH für AmigaOS 4.1 – Beta 1

Dies ist die erste Beta-Version von **CorsixTH für AmigaOS 4.1**, angepasst für PowerPC-basierte AmigaOS-Systeme.

CorsixTH ist eine Open-Source-Neuimplementierung der Spiel-Engine des klassischen Krankenhaus-Simulationsspiels *Theme Hospital*. Mit CorsixTH kann das Spiel mit den Original-Spieldaten gespielt werden.

## Beta-Status

Diese Version ist eine frühe Beta und für Tests auf echter AmigaOS-4.1-Hardware vorgesehen.

- Erstellt für AmigaOS 4.1 auf PowerPC-Systemen.
- Erste Tests auf einem Pegasos II.
- Erste Anpassungen für AmigaOS-spezifische Dateipfade.
- Die Original-Spieldaten von Theme Hospital werden benötigt und müssen separat bereitgestellt werden.
Support und anfragen bitte auf A1k stellen:
https://www.a1k.org/forum/index.php?threads/98827/
## Voraussetzungen

- AmigaOS 4.1 auf einem unterstützten PowerPC-System.
- Die Original-Spieldaten von Theme Hospital.
- Ausreichend Arbeitsspeicher und Festplattenplatz für das Spiel und die Spieldaten.

## Installation

1. Das LHA-Archiv in ein Verzeichnis deiner Wahl entpacken.
2. Sicherstellen, dass die benötigten Theme-Hospital-Spieldaten im vorgesehenen Verzeichnis vorhanden sind.
   Es wurde mit der GOG-Version getestet. Bitte kopiert die Daten nach ThemeHospital.
3. Die gegebenenfalls beiliegenden Installationshinweise beachten und CorsixTH starten.

## Hinweise zur Beta

Diese Version befindet sich noch in der Entwicklung. Fehler, Kompatibilitätsprobleme und Leistungseinschränkungen sind daher möglich.

Rückmeldungen, Fehlerberichte und Hinweise zur Kompatibilität mit unterschiedlichen AmigaOS-4.1-Systemen sind willkommen.

Was noch nicht geht:
- Fullscreen hier liegt es aber an der minigl.library die einiges nicht unterstützt.Hier muss ich noch sehen wie ich das löse.
- Musik hier arbeite ich noch dran.

Bitte in der config.txt auch nicht die Werte dafür anschalten.


## Rechtliche Hinweise

CorsixTH ist ein unabhängiges Open-Source-Projekt und steht in keiner Verbindung zu den ursprünglichen Herausgebern von Theme Hospital.

Die Original-Spieldaten sind nicht enthalten. Sie unterliegen weiterhin den jeweiligen Urheberrechten und müssen vom Benutzer selbst bereitgestellt werden.

**Version:** 0.70.1-dev269 – AmigaOS 4.1 Beta 1  
**Plattform:** AmigaOS 4.1 / PowerPC


englisch:# CorsixTH for AmigaOS 4.1 – Beta 1

This is the first beta release of **CorsixTH for AmigaOS 4.1**, adapted for PowerPC-based AmigaOS systems.

CorsixTH is an open-source reimplementation of the game engine for the classic hospital management simulation *Theme Hospital*. It allows you to play the game using the original game data.

## Beta Status

This is an early beta release intended for testing on real AmigaOS 4.1 hardware.

- Built for AmigaOS 4.1 on PowerPC systems.
- Initial testing on a Pegasos II.
- Initial adaptations for AmigaOS-specific file paths.
- The original *Theme Hospital* game data is required and must be supplied separately.
For support and inquiries, please use the A1k forum:

https://www.a1k.org/forum/index.php?threads/98827/

## Requirements

- AmigaOS 4.1 running on a supported PowerPC system.
- The original *Theme Hospital* game data.
- Sufficient RAM and disk space for the game and its data files.

## Installation

1. Extract the LHA archive to a directory of your choice.
2. Make sure the required *Theme Hospital* game data is available in the designated directory. The GOG version has been tested. Please copy the game data into the `ThemeHospital` directory.
3. Follow any additional installation instructions included in the archive, if applicable, and start CorsixTH.

## Beta Notes

This version is still under development, so bugs, compatibility issues and performance limitations may occur.

Feedback, bug reports and information about compatibility with different AmigaOS 4.1 systems are welcome.

### Known Limitations

- **Fullscreen mode:** Currently not working. This appears to be due to limitations in `minigl.library`, which does not support some of the required features. I still need to investigate possible solutions.
- **Music:** Music playback is not working yet. I am still working on it.

**Please do not enable the corresponding options in `config.txt` for now.**

## Legal Notice

CorsixTH is an independent open-source project and is not affiliated with or endorsed by the original publishers of *Theme Hospital*.

The original game data is not included. It remains subject to the respective copyrights and must be provided by the user.

**Version:** 0.70.1-dev269 – AmigaOS 4.1 Beta 1  
**Platform:** AmigaOS 4.1 / PowerPC
