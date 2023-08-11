# Notes

## During Development
- Edit in Traktor > Controller Manager
- Export from Traktor and replace `.tsi` file here
- Push to Github

## Quick Install in Traktor
- Open `Settings > Controller Manager`
- Click `Add > Import TSI > Import Other...`
- Select TSI in this folder

## Controllers
- Allen & Heath K1 and K2 controllers
- USB from laptop to K2
- XLink from K2 to K1

## Traktor Audio & Output Routing
- `Settings > Audio Setup`
  - We're using internal mixing mode, so choose XONE:K2 as Audio Device
- `Settings > Output Routing`
  - Output Master from main (rear) outs
    - These appear as 3: Front Center and 4: Low Freq Effects
    - Send to front of house
  - Output Monitor from front out
    - These appear as 1: Front Left and 2: Front Right
    - Headphones

## MIDI Setup
- Midi Channels
  - K2: Channel 12
  - K1: Channel 11
  - To change channels, hold "Power On Setup" and power on the controllers. See Allen & Heath User Guide for more info
