# Soil-Humidity-Monitor

## Hardware
NodeMCU  
Soil Humidity Sensor  

## Software
Firebase  
NodeJS  

## Debug
Error: Unable to parse JSON: SyntaxError: Unexpected token / in JSON at position 37  
Error: Unable to parse JSON: SyntaxError: Unexpected token } in JSON at position 60  

database.rules.json MUST MODIFIED as below:
```bash
{
  "rules": {
    ".read": "true",
    ".write": "true"
  }
}
```
## Reference
https://randomnerdtutorials.com/esp32-esp8266-firebase-gauges-charts/  
https://randomnerdtutorials.com/esp8266-nodemcu-firebase-web-app/
