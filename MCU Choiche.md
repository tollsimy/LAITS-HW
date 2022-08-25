# MCU Choice
Wi-Fi -> ESP32

ESP32 Models:
- ESP8266 Series
- ESP32 Series
- ESP32-S Series
- ESP32-C Series

Constraints:
- Ipex antenna as well as PCB antenna.
- BLE
- Available in castellated holes module version

## Results (non NRND)
- ESP32-C3-MINI-1U
- ESP32-C3-WROOM-02U
- ESP32-WROOM-32UE (4MB/8MB/16MB)
- ESP32-WROVER-IE

## Comparison
- ESP32-C3 is single core,ESP32 is dual core.
- ESP32 CPU clock 240 MHz while ESP32-C3 is 160MHz.
- the two ESP32-C3 modules are smaller than ESP32 modules.
- ESP32-C3 BLE is V5.0 while ESP32 BLE is V4.2.
- ESP32-C3 has 15 pins, ESP32 has 26 (WROOM-32UE) or 24 (WROVER_IE, probably because of PCB antenna and ipex selector).
- ESP32 has more SRAM, ROM and RTC SRAM that ESP32-C3.
- ESP32-WROVER-IE has 8MB of PSRAM.
- ESP32-WROVER_IE has also PCB antennas.

## Availability
- ESP32-WROOM-32UE-N4 (4MB) is available on mouser for 2.73 euro.
- ESP32-WROVER-IE-N4R8 is available on mouser for 3.00 euro.

## Final Result
**ESP32-WROVER-IE**
