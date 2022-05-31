# Soil-Humidity-Monitor

## Website URL  
https://soil-monitor-35fec.web.app/

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
* tutorial  
https://randomnerdtutorials.com/esp32-esp8266-firebase-gauges-charts/  
https://randomnerdtutorials.com/esp8266-nodemcu-firebase-web-app/  

* 網頁顯示工具(圖表、儀錶板顯示...)  
https://developers.google.com/chart

* firebase deploy 問題 debug  
https://blog.csdn.net/u010393758/article/details/53737220  
https://stackoverflow.com/questions/5690269/disabling-chrome-cache-for-website-development

* website design template reference  
https://www.pinterest.com/pin/535435843209013861/  

* Show current time  
https://www.wibibi.com/info.php?tid=175  
