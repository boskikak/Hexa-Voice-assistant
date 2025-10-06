# Hexa-Voice-assistant
Voice Assistant based on ESP32 S3 N16R8 with stereo speakers and simply led clock.

## 1. Hardware:
- ESP32 S3 N16R8
- 2x speakers 52mm 5W 4ohm
- PCM5102
- PAM8406
- microphone INMP411
- led ring 85mm (24diodes)
- buzzer 3V
- speaker fabric
- capacitor 1000uF 10V
- usb C socket
- usb C cable
- 3 tact switch 6x6 h=8
- 6x bolt M2.5x6
- speaker fabric

## 2. Schema
![HEX](https://github.com/user-attachments/assets/d7fc0e55-0f02-47ec-b565-0f37cba82fc2)


 & PCM & ESP32 jumpers

![pcm](https://github.com/user-attachments/assets/1720eb65-d165-407f-b6a2-816969771dd6)
![esp jumper](https://github.com/user-attachments/assets/0e610223-f114-4200-a676-652226e11f2d)


## 3. Short description
The most important settings are at the top of the code. The wake word is alexa but can be changed according to [microwakeword models](https://github.com/esphome/micro-wake-word-models/tree/main/models). The clock displays the time with an accuracy of 2.5 minutes. 
You can set a separate volume level for the assistant and listening time. Also you can deactivate assist and turn off clock.
![encje](https://github.com/user-attachments/assets/1a13426e-df0e-45d2-a6f0-30e610c2dd47)


## 4. Step by step
![IMG_20250608_170114694_HDR](https://github.com/user-attachments/assets/f61c8774-14b3-423d-b945-7c8f43d6437a)
![IMG_20250608_170149499_HDR](https://github.com/user-attachments/assets/12038699-115c-45fd-9ebd-e1141d13a1dd)
![IMG_20250612_101720290_HDR](https://github.com/user-attachments/assets/3df934dd-035e-4453-9cf4-878ad39db364)
![IMG_20250612_110514494_HDR](https://github.com/user-attachments/assets/8c7f466b-2a7c-419c-8564-293a3e535ba8)
![IMG_20250612_110525650_HDR](https://github.com/user-attachments/assets/f3a5a0f7-68bb-4186-adf8-f0eeee6d9596)
![IMG_20250612_111428452_HDR](https://github.com/user-attachments/assets/c09b5971-8ed2-456c-bd2e-c5a20b488a4b)


## 5. Effects
![IMG_20250608_104713100_HDR](https://github.com/user-attachments/assets/3f8e5fb1-b406-4fe7-aa1e-27d7237aaf30)
![IMG_20250509_204240465_HDR](https://github.com/user-attachments/assets/235af48c-3076-44da-9155-898e89f211a5)
![IMG_20250509_204300825_HDR](https://github.com/user-attachments/assets/85d20477-faa1-45ba-997a-93deab3a0b9d)
![IMG_20250509_204336373_HDR](https://github.com/user-attachments/assets/2da49421-44b0-4bc8-a23d-753c527bdf27)
![IMG_20250509_204452141_1](https://github.com/user-attachments/assets/7097dec2-f08d-48ca-9de9-8c2a83cad397)

## 6. Summary
I recommend a 2A or 3A power supply for the speaker. Printing profiles you can find [here](https://makerworld.com/en/models/1520535-hexavoice-assistant#profileId-1593371)

## 7. What's news?

09.2025:
 - double click play button to unable/enable microphone
 - click at the same time vol+ & vol- to restart device

10.2025
  - stereo sounds with Esphome >2024.5 (using old libraries i2s)
  - choose from list your wake word and set your first choice
   

