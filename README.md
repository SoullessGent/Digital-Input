# Digital-Input
Digital input button switches

This project uses:
2 x button switch
1 x ESP32
1 x 220 resistor
1 x led (blue in this case)
7 x jumper wires

D18 -> LED

D19 -> switch A

D21 -> switch B

For this project the idea is that when you push a button it send the the current to ground thus creating a "low" state and when the current is low the program will do one of two things. If the button that sent the current low was switch A then it would turn the light on, if the button was switch B then it will turn the light off. this will always be the case even if the button is already in the sate that the respective button will switch to. Kind of like a light switch. you can turn it on and no matter how many times you push the on button it will just be on.
