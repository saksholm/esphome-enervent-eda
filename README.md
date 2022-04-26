# esphome-enervent-eda
ESPHome Enervent EDA

This project is used to control the Enervent EDA over ESPHome.

#### Hardware used in this project:
- Wemos D1 Mini
- TTL-MAX485 converter
- Enervent EDA automation
- RJ14 cable to connect EDA automation to TTL converter

#### Config
- enervent.yaml (configuration file for ESPHome)
- Wemos TX pin GPIO15 (D8) -> TX pin of TTL converter
- Wemos RX pin GPIO13 (D7) -> RX pin of TTL converter
- Wemos 5V pin -> VCC pin of TTL converter
- Wemos G pin -> GND pin of TTL converter