# OOAD-WEEK09 Homework
##ส่งการบ้าน Class Diagram นวเขตต์ พลอยโพธิ์ 57030182
###USE CASE 1.
   Code
   ```
@startuml

title Classes - Computer

class CASE{
   +Mainboard
   +Harddisk
   +Cpu
   +Rom
   +Ram
   +Power Supply
}
class DISPLAY{
   +Mainbord
   +Power Supply
   +Screen
}
computer*-down- mouse
computer*-down- keyboard
computer*-down- loudspeaker
computer*-down- DISPLAY
computer*-down- CASE
@enduml

   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/PL2x3i8m3Dpp5Pv1_OTM0Gaaa2eoCOR6GzMy52UgAiI_qxGPe9tEFjkdEzSKPOZ9QCPY7pK2rv882IhWplWKCJ3MPGvu8yvl1W37k-pjoycWbkuo5wgdOMcuJmi-d5bHhjYw4GE8vBsUsASedgwYlJNFNz6Y-RUU2T45H9ilYwj3fTneAp0k4UxO0QVLu7QWNLBaKGvphksisDdnEJYhqQhvJLy0">
 
###USE CASE 2.
   Code
   ```
@startuml

title Classes - Smartphones

Smartphones*-down- battery
Smartphones*-down- Mainboard
Smartphones*-down- loudspeaker
Smartphones*-down- speaker
Smartphones*-down- DISPLAY
Smartphones*-down- CASE
Smartphones*-down- Keypad
@enduml

   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/VS-n2eCm4CRn_PuYSo7le6Y7ea8XKyUJEwWOav0x4T--ZWv7n-__cxv65AlkMmJGHIExBg88Y_CkR9UKRqui0BVny9IFvDsCgbnFYoPSqfonaeKnxoI5SULgyH_gN-4zjX-BkZOyhJxmMP2WuKJNoHy0"> 

###USE CASE 3.
   Code
   ```
@startuml

title Classes - car

class Control{
   +steering wheel
   +gear
   +Switch lights
}

car*-down- wheel
car*-down- engine
car*-down- carriage
car*-down- Control

@enduml

   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/LOv12iCm30JlUeNEBVv384_e2umZR84gWwJWG-ZVwvGSqjlkiClkuf4jzhS018SGhfBToJ5XoGPGJejhrx0k1o3YquF8M2kEHYG_L6bcJ_4Q7AMXS6tXy9dzR8-qzQ7fYjy0QMMbEvdIEDS_Tcq3BAJRFFe5"> 

###USE CASE 4.
   Code
   ```
@startuml

title Classes - Fan

class Control{
   +Switcher
}

Fan*-down- propeller
Fan*-down- Moter
Fan*-down- case
Fan*-down- Control

@enduml


   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/LOun2eGm44NxVugfLtA7W61dvGb275XXp4Xc9CMoTpV25cxv7f_7Z-Qf-haBu9iBqoZ9Z8q2JQa0-KOQjNXL-O28XgLjdjzSyGNwvXLMRINGKVLWaUuVSbR_5paPF_bN1YANjT-u0000"> 

###USE CASE 5.
   Code
   ```
@startuml

title Classes - CD PLAYER
left to right direction
class PLAYER{
   -Make :String
   -Model :String
   +PLAY()
   +PAUSE()
   +STOP()
}
class CD{
   -Artist :String
   -Title :String
   +Locate Track()
}
PLAYER --> CD
@enduml

   ```
Diagram

<img src="http://www.plantuml.com/plantuml/img/LO-n3e8m68JtFiMD6jCNS30GOCD810V7flnYGwL9-piPtzr26N2xNBvykSi2Ay_lbnM23Lj2OLK8521Hb6Zg_5vTXQK7Wnsy6PwCtdZIRDmazCokq4S0a6Sr4eujUpCDgN0zsMrpcF7TFiNyrbPhRhjB4-DtbHPb4kQUJU0_PRVit2fhfnKJEg_qk3ZI94XvYYAHqTJ7Xpy0"> 
