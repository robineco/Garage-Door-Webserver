# Garage-Door-Webserver
Webserver on an ESP8266 that can control a remote garage door relay

## Captured signal from garage door remote control
![Signal](https://raw.githubusercontent.com/robineco/Garage-Door-Webserver/master/images/signal-a.png)

## Decoded signals in Universal-Radio-Hacker
![Signals](https://raw.githubusercontent.com/robineco/Garage-Door-Webserver/master/images/signal-analyze.png)


Bits sent to trigger the relay A
```
011110100111000000100001
```
Bits sent to trigger the relay B
```
011110100111000000100010
```
Bits sent to trigger the relay C
```
011110100111000000100100
```
Bits sent to trigger the relay D
```
011110100111000000101000
```

## Webserver interface to control the garage door with the esp8266
![Webserver](https://raw.githubusercontent.com/robineco/Garage-Door-Webserver/master/images/webserver.png)