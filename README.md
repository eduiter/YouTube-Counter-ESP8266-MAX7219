# YouTube-Counter-ESP8266-MAX7219

## Usage

### Connections for ESP8266 hardware SPI
```
// Vcc       3v3     LED matrices seem to work at 3.3V
// GND       GND     GND
// DIN        13     HSPID or HMOSI  OR D7
// CS or LD   15     HSPICS or HCS  OR D8
// CLK        14     CLK or HCLK or D5
```

### Replace the Follwing
```
char ssid[] = "****";       // your network SSID (name)
char password[] = "***";  // your network key
#define API_KEY "****"  // your google apps API Token
#define CHANNEL_ID "UCCh3TTc3AoqsyF3iCMU6AqA" // makes up the url of channel
```
