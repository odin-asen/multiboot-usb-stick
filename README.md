# Zweck
Konfigurationsdateien für einen Multiboot-USB-Stick auf Basis von YUMI-UEFI mit folgenden Programmen
* Arcronis Disk Director 12
* Acronis TrueImage 2017
* Disk EaseUS 10.5
* Kaspersky Recovery Disk

# Installationsschritte
1. YUMI-UEFI runterladen (Version: 0.0.1.3) 
    * https://www.pendrivelinux.com/yumi-multiboot-usb-creator/
2. Images installieren
    * Für jedes Image YUMI-UEFI einmal als Administrator ausführen
    * &#9888; Manche Links zu ISO-Dateien existieren nicht mehr und müssen über einen anderen Weg dem Programm übergeben werden
    1. Acronis TrueImage
    2. Kaspersky Recovery Disk (&#9888; siehe Anmerkung zu Kaspersky)
    3. Disk EaseUS
3. Aus diesem Repository Unterordner und Dateien von multiboot-config auf nach multiboot auf den Stick kopieren
    * Alle identischen Dateien und Ordner überschreiben

## Anmerkung zu Kaspersky
Nach der Installation auf den Stick, muss der Ordner *data* auf die erste Ebene verschoben werden.
