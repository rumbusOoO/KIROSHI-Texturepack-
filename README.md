
[![YouTube Showcase](https://img.shields.io/badge/YouTube-Showcase-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=c_yETqIBHyI)

# KIROSHI

Cyberpunkowy edytor/narzędzie do texturepacków dla Minecraft Java 1.21.2–1.21.4.

⚠️ Beta 1.0

---

## O projekcie

KIROSHI to samodzielna aplikacja GUI stworzona do edytowania i rozszerzania texturepacków Minecrafta przy pomocy shaderów oraz własnych plików konfiguracyjnych.

Program automatycznie odczytuje i edytuje `setting.glsl`, dynamicznie generuje GUI, obsługuje różne tryby konfiguracji oraz potrafi dograć wymagane pliki KIROSHI bezpośrednio do wybranego texturepacka.

Projekt był pierwotnie tworzony pod OptiFine 1.21.4, ale działa również na Vanilla 1.21.2–1.21.4.

Repozytorium zawiera jedynie skompilowaną wersję `.exe`.

---

## Główne funkcje

* Dynamiczne GUI generowane z `setting.glsl`
* Automatyczny parser:

  * bool
  * int
  * float
  * vec3
  * vec4
* Ciemny cyberpunkowy motyw GUI
* Wybór texturepacka z `.minecraft/resourcepacks`
* System Inject do instalacji plików KIROSHI
* System Destroy do usuwania plików Inject
* Automatyczne backupy przed każdym zapisem
* Tryb Emergency OFF
* Wyszukiwarka ustawień
* Tryby Noob / Pro / Expert
* Edytor kolorów RGB z podglądem
* Zakładki generowane z sekcji shaderów
* Edycja konfiguracji GLSL bez niszczenia komentarzy i kolejności ustawień

---

## System Inject

Aplikacja posiada wbudowane szablony shaderów bezpośrednio w `.exe` i nie wymaga dodatkowych plików poza wybranym texturepackiem.

Inject potrafi:

* dograć wymagane pliki KIROSHI,
* tworzyć backup przed nadpisaniem,
* losować daty modyfikacji plików,
* automatycznie odtwarzać brakujące pliki.

---

## Tryby GUI

### Noob

Pokazuje tylko najważniejsze opcje:

* ESP
* tracery
* night vision
* nametagi
* invis particle
* kolory/lightmapy

### Pro

Pokazuje wszystkie bezpieczne przełączniki i ustawienia kolorów.

### Expert

Pokazuje wszystkie zmienne dostępne w `setting.glsl`.

---

## Bezpieczeństwo i backupy

* Automatyczne backupy przed zapisem
* Walidacja wartości RGB/XYZ
* Blokowanie nieprawidłowych wartości
* Ostrzeżenia przed nadpisaniem
* Możliwość przywracania plików
* Emergency OFF z backupem
* Destroy usuwa tylko znane pliki KIROSHI

---

## Jak używać

1. Pobierz najnowsze `.exe`
2. Uruchom aplikację
3. Wybierz texturepack
4. Zmień ustawienia
5. Zapisz zmiany
6. W Minecraft użyj:

F3 + T

aby przeładować texturepack.

---

## Kompatybilność

Polecane:

* OptiFine 1.21.4

Wspierane:

* Vanilla 1.21.2 – 1.21.4

---

## Disclaimer

Użytkownik korzysta z programu na własną odpowiedzialność.

Autor projektu nie ponosi odpowiedzialności za:

* bany,
* ograniczenia,
* blacklisty,
* wykrycia,
* utratę konta,
* ani jakiekolwiek konsekwencje wynikające z używania programu lub zmodyfikowanego texturepacka na serwerach Minecraft.

KIROSHI jest projektem eksperymentalnym/beta i może działać inaczej w zależności od:

* wersji gry,
* klienta,
* shaderów,
* resource packa,
* serwera,
* antycheata,
* lub konfiguracji użytkownika.

---

# KIROSHI

Cyberpunk-inspired texturepack editor/tool for Minecraft Java 1.21.2–1.21.4.

⚠️ Beta 1.0

---

## About

KIROSHI is a standalone GUI application designed for editing and extending Minecraft texturepacks through shader-based configuration and injected files.

The application automatically reads and edits `setting.glsl`, dynamically generates GUI controls, supports multiple configuration modes, and can inject required KIROSHI shader files directly into the selected texturepack.

Originally created for OptiFine 1.21.4, but compatible with Vanilla 1.21.2–1.21.4.

This repository contains only the compiled `.exe` release.

---

## Main Features

* Dynamic GUI generated from `setting.glsl`
* Automatic parser for:

  * bool
  * int
  * float
  * vec3
  * vec4
* Dark cyberpunk-style interface
* Texturepack selector from `.minecraft/resourcepacks`
* Inject system for installing KIROSHI files
* Destroy system for removing injected files
* Automatic backups before every save
* Emergency OFF mode
* Search system for settings/options
* Noob / Pro / Expert modes
* RGB color editor with preview
* Tabs generated from shader sections
* GLSL configuration editing without breaking comments/order

---

## Inject System

The application contains embedded shader templates directly inside the executable and does not require external assets besides the selected texturepack.

Inject can:

* install required KIROSHI files,
* create backups before overwrite,
* randomize modification dates,
* automatically restore missing files.

---

## GUI Modes

### Noob

Shows only the most important options:

* ESP
* tracers
* night vision
* nametags
* invis particles
* colors/lightmaps

### Pro

Shows all safe switches and color settings.

### Expert

Displays every editable variable from `setting.glsl`.

---

## Safety / Backup Features

* Automatic backups before save
* RGB/XYZ validation
* Invalid value protection
* Overwrite warnings
* Restore support
* Emergency OFF backup system
* Destroy removes only known KIROSHI files

---

## Usage

1. Download the latest `.exe`
2. Open the application
3. Select your texturepack
4. Modify settings
5. Save changes
6. Reload the texturepack in Minecraft using:

F3 + T

---

## Compatibility

Recommended:

* OptiFine 1.21.4

Supported:

* Vanilla 1.21.2 – 1.21.4

---

## Disclaimer

Users use the program at their own risk.

The author is not responsible for:

* bans,
* restrictions,
* blacklists,
* detections,
* account loss,
* or any consequences caused by using the program or modified texturepacks on Minecraft servers.

KIROSHI is an experimental/beta project and may behave differently depending on:

* game version,
* client,
* shaders,
* resource pack,
* server,
* anti-cheat,
* or user configuration.
