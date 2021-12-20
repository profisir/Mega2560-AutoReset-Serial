# Mega2560-AutoReset-Serial-Optiboot
Automatyczne resetowanie arduino Mega 2560 podczas inicjalizacji programowania Arduino przez serial WiFi lub LAN w zależności jak
Arduino automatycznie samo się resetuje po wykryciu wysłanej sekwencji programowania (Optiboot).
Wyjście Arduino D12 - R1K - ULN2004 > -<dioda_shotky< - Pin Reset Arduino
- Zmieniony Bootloader w Mega 2560 na Optiboot
- Moduły do komunikacji z Arduino Mega:
- WiFi - ESP8266 z esp-link - posiada opcje resetowania ale trzeba użyć odpowiedniego oprogramowania typu Megaload.
- LAN - Eport PRO EP20PRO linux (hi-flying)- tryb Serial
- TCP/UDP to IP Socket - Virtual port pod Windows 10 - Net Burner Virtual Com Port wersja 2.1 (nie działa zmiana Baud Rate)
