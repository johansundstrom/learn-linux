# learn-linux
Kom igång med några enkla första steg. Oavsett om du använder MAC, Linux Debian eller Raspbian. Följande instruktioner är i första hand för Raspberry Pi

## Raspberry Pi

Installera OS på det enklaste sättet

1. Ladda ned Raspian ```https://www.raspberrypi.org/downloads```
2. Ladda ned BalenaEtcher ```https://www.balena.io/etcher```
3. Starta BalenaEtcher och markera ```.bin``` filen
4. Markera SD-minnet (gör inte fel här)
5. Klicka Flash!
6. Flytta SD-kortet till RPI och starta upp

## Login och uppdatera RPI

1. AID: pi
2. PWD: raspberry
3. Öppna ett terminalfönster
4. Uppdatera genom ```sudo apt-get update``` (uppdaterar lista över möjliga uppdateringar)
5. Genomför uppdateringar ```sudo apt-get upgrade```
6. Genomför punkt 3-5 inför varje ny installation av tillägg på RPI

## Leta efter anslutna USB-enheter

```ls -l /dev/cu.us*```

## Använd bash som terminal till USB-port

```sudo tail -f /dev/cu.usbserial-14520```
