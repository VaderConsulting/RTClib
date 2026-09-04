# RTClib

A fork of Jeelab's fantastic RTC library. Works with DS1307, DS3231, PCF8523, PCF8563 on multiple architectures Original author: Adafruit. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 2.0.2. Upstream: <https://github.com/adafruit/RTClib>.

**Source last updated:** 2021-12-21  
**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `RTClib` | C++ / Arduino | library | A fork of Jeelab's fantastic RTC library |
| `DS3231_alarm` | C++ / Arduino | example sketch | `examples/DS3231_alarm/DS3231_alarm.ino` |
| `customWire_DS3231onSAMD21` | C++ / Arduino | example sketch | `examples/customWire_DS3231onSAMD21/customWire_DS3231onSAMD21.ino` |
| `datecalc` | C++ / Arduino | example sketch | `examples/datecalc/datecalc.ino` |
| `ds1307` | C++ / Arduino | example sketch | `examples/ds1307/ds1307.ino` |
| `ds1307SqwPin` | C++ / Arduino | example sketch | `examples/ds1307SqwPin/ds1307SqwPin.ino` |
| `ds1307nvram` | C++ / Arduino | example sketch | `examples/ds1307nvram/ds1307nvram.ino` |
| `ds3231` | C++ / Arduino | example sketch | `examples/ds3231/ds3231.ino` |
| `interrupts1Hz` | C++ / Arduino | example sketch | `examples/interrupts1Hz/interrupts1Hz.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/RTClib`). Open any `examples/*.ino` from the Arduino IDE.

## Requirements

- Arduino IDE

## Attribution and provenance

- **Original author / maintainer:** Adafruit
- **library.properties name:** RTClib
- **Version:** 2.0.2
- **Upstream URL:** <https://github.com/adafruit/RTClib>
- **Category:** Timing
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Mit terms recorded in `license.txt`. This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
