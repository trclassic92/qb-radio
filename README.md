# qb-radio
qb-radio Nopixel Inspired Radio for qb-core

## Install Video
- [Youtube](https://youtu.be/bNrmQMvVYno)

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [pma-voice](https://githubmate.com/repo/AvarianKnight/pma-voice)
- [qb-radialmenu](https://github.com/qbcore-framework/qb-radialmenu) - Optional (Access to change channels 1 - 4)

## Features
- Nopixel Inspired Radio
- Radialmenu join channel option 1 - 6
- Inventory Image [qb-radio/imgforinvenotry]

## RadialMenu Events
Add the trigger to your qb-radialmenu > config.lua (Anywhere you want someone to have access to it) for example:
```
            id = 'joinradio1',
            title = 'Channel 1',
            icon = 'radio',
            type = 'client',
            event = 'qb-radio:client:JoinRadioChannel1',
            shouldClose = true
```
Credits to MonkeyWhisper for creating the event

## Images
- Google search for the image of the radio https://i.imgur.com/pgRGFIB.png
![Preview Screenshot](https://i.imgur.com/4gpPbXm.png)
- Preview of the radio https://youtu.be/vMr-OFP8HzU

## Installation
- Replace current qb-radio with this version if you want to use it

1/12/2022 (Radio Effects)
-  To add the new radio sounds go to `\pma-voice\ui`

Inventory image - replace radio.png in your current inventory image folder with this one.

## Discord
- [Join Discord](https://discord.gg/T2xX5WwmEX)

## Support
- [Ko-fi Link](https://ko-fi.com/trclassic)

## Original qb-radio
- [qb-radio](https://github.com/qbcore-framework/qb-radio)
