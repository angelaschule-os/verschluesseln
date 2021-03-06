[![CC BY 4.0][cc-by-shield]][cc-by]


[cc-by]: https://creativecommons.org/licenses/by/4.0/deed.de
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

# Datenschutz

- [Datenschutz](#datenschutz)
  - [Wo finde ich Informationen](#wo-finde-ich-informationen)
    - [Linkhaufen](#linkhaufen)
  - [Einstieg](#einstieg)
  - [BitLocker (Windows)](#bitlocker-windows)
  - [VeraCrypt (Windows / Linux / MacOS)](#veracrypt-windows--linux--macos)
    - [Hinweise zur Installation und Nutzung](#hinweise-zur-installation-und-nutzung)
    - [Links](#links)
  - [weitere Möglichkeiten](#weitere-möglichkeiten)
    - [Gpg4win (Windows)](#gpg4win-windows)
    - [GPG Suite (MacOS)](#gpg-suite-macos)
    - [7zip (Windows / Linux)](#7zip-windows--linux)
  - [Exkurs mobile Endgeräte](#exkurs-mobile-endgeräte)

## Wo finde ich Informationen

- Ansprechpartnerin: Andrea Bielevelt
- Technischer Ansprechpartner: Björn Schilberg

### Linkhaufen

- https://lwiki.angelaschule-os.de/doku.php?id=datenschutz
- https://lfd.niedersachsen.de/startseite/themen/schulen/datenschutz-in-schulen-56175.html
- https://www.landesschulbehoerde-niedersachsen.de/themen/schulorganisation/datenschutz/dsgvo/faq-ds-gvo
- https://lfd.niedersachsen.de/download/153559/Erlass_zur_Verarbeitung_personenbezogener_Daten_auf_privaten_IT-Systemen_von_Lehrkraeften.pdf


## Einstieg

Wer hat schon mal seine Daten versucht zu verschlüsseln?

Wenn nicht warum?

- Angst vor Daten-Verlust
- Zu kompliziert
- Keine Lust
- Sinn nicht klar

Was kann verschlüsselt werden:

- Dateien
- Ordner
- Laufwerke: Festplatten, USB-Sticks
- (Emails) -> Extra Thema

Ist das nicht langsam?
- Kommt drauf an.

## BitLocker (Windows)

BitLocker ist eine Festplattenverschlüsselung des Unternehmens
Microsoft. BitLocker ist proprietäre Software.

Achtung: In Windows 10 Home Edition nicht verfügbar!

Vorteile BitLocker:
- Einfache Benutzerführung zur Verschlüsslung von USB-Sticks.
- Wiederherstellung-Schlüssel, falls Passwort vergessen oder verloren. Am
  Besten ausgedruckt im Safe aufheben.

Theoretisch minimaler meßbarer Leistungsnachteil. Praktisch kaum wahrnehmbar.

- https://de.wikipedia.org/wiki/BitLocker
- https://docs.microsoft.com/de-de/windows/security/information-protection/bitlocker/bitlocker-frequently-asked-questions

## VeraCrypt (Windows / Linux / MacOS)

VeraCrypt ist eine Software zur Datenverschlüsselung, insbesondere zur
vollständigen oder partiellen Verschlüsselung von Festplatten und
Wechseldatenträgern. VeraCrypt ist Freie Software.

Alternative ist BitLocker von Microsoft.

Achtung es gibt anders als bei BitLockler keinen Wiederherstellungsschlüssel.
Wenn Passwort verloren oder vergessen, dann sind die Daten futsch.

Theoretisch minimaler meßbarer Leistungsnachteil. Praktisch kaum wahrnehmbar.
Gilt für die Festplattenverschlüsselung.

Vorteil: VeraCrypt ist flexibel einsetzbar unter Windows / Linux / MacOS.

Besonderheit: Container/Datei als virtuelles Laufwerk!

### Hinweise zur Installation und Nutzung

- [Hinweise zur Installation und Nutzung](./VeraCrypt.md)

### Links

- https://www.heise.de/select/ct/2020/17/2017718561505911688
- https://www.heise.de/tipps-tricks/VeraCrypt-Alles-verschluesselt-4308944.html

Fall: Anwalt wird in der Bahn der Laptop geklaut und wird erpresst.

## weitere Möglichkeiten

### Gpg4win (Windows)

Gpg4win (GNU Privacy Guard for Windows) ist ein Installationspaket für Windows
zur E-Mail- und Datei-Verschlüsselung. Gpg4win ist Freie Software.

- https://www.gpg4win.de/

Was kann verschlüsselt werden:
- Dateien
- Ordner
- Emails

- https://www.datenschutz.rlp.de/fileadmin/lfdi/Dokumente/OH_GPG_fuer_Windows.pdf
- https://www.heise.de/ct/artikel/Einfach-erklaert-E-Mail-Verschluesselung-mit-PGP-4006652.html


### GPG Suite (MacOS)

GPG Suite ist ein Installationspaket für Apples macOS, zur E-Mail und
Datei-Verschlüsselung. GPG Suite ist Freie Software.

- https://gpgtools.org/
- https://www.datenschutz.rlp.de/fileadmin/lfdi/Dokumente/OH_GPGTools_fuer_Mac.pdf

### 7zip (Windows / Linux)

7zip ist ein Packprogramm. Welches Verschlüsselung unterstützt. 7zip ist Freie
Software.

- https://www.7-zip.de/

Was kann verschlüsselt werden:
- Dateien
- Ordner


## Exkurs mobile Endgeräte

Mobile Endgeräte. Kein speichern von vertraulichen Daten!!!
