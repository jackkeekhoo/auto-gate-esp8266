# auto-gate-esp8266
using esp8266 to control auto gate / garage door (with existing board intact)

the controller esp8266 act as wifi station mode, and handle few server arguments, gateboth, gateleftopen, gaterightopen and gateswitchside
esp8266 IP/input?gateboth=3000 <- this will initiate the door to open, and delay(3000), and then stop the door

web browser controller contain lots of button that link to javascript function. Function will finalize the parameters and will refresh a html "<iframe>" which iframe links to the esp8266 

