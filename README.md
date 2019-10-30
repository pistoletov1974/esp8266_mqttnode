# esp8266_mqttnode
MQTT node for control 2812 strip and some on/off gpio. With sensor: DUST, AIR Quailty Temp Humi &amp; Pressure. Output in MQTT JSON format

{
  "state": "OFF",
  "powerOn": "OFF",
  "DC5V1On": "OFF",
  "DC5V2On": "OFF",
  "brightness": 255,
  "effect": "solid",
  "frame": "OFF",
  "color": {
    "r": 255,
    "g": 255,
    "b": 255
  },
  "bme280": {
    "temp": 27.38,
    "humi": 36.7207,
    "press": 750.2596
  },
  "ccs811": {
    "CO2": 400,
    "TVOC": 0
  },
  "sds": {
    "pm25": 3.8
  }
}
