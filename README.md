# WireGuard-OS-RPI
<sup><span style="font-size: 0.8em; color: #888;"><i>projekt szkolny</i></span></sup>

Najnowszy system image znajduje się w zakładce **Releases**.

System jest bootowalny i przetestowany na Raspberry Pi 5. Aby działał poprawnie na modelu docelowym, kernel może wymagać dodatkowej personalizacji, choć nie koniecznie będzie to wymagane. // NAJNOWSZA WERSJA DZIALA NA RPI W02

## Roadmap (kolejność może się zmienić)

* Instalacja OpenSSH 9.9p2 // ZROBIONE
* Konfiguracja urządzeń sieciowych: `eth0` i `wlan0` // ZROBIONE
* Kompilacja nowego jądra z modułami wymaganymi przez dokumentację WireGuard // ZROBIONE
* Instalacja i konfiguracja WireGuard

## Znane błędy

W systemie występują dwa znane błędy podczas uruchamiania. Zostaną one naprawione w kolejnych wydaniach. // NAPRAWIONE

## Uwaga dotycząca rozruchu

Obecnie może być konieczne ręczne zmodyfikowanie wpisu `root=<foo>` w pliku `/boot/cmdline.txt`, tak aby wskazywał na właściwą partycję root (np. `mmcblk0p2`). Będzie to zmienione. // NAPRAWIONE
