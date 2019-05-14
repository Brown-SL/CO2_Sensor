# Read Me

Hello!

This is to support the article:
Brown, S.L., Goulsbra, C.S., Evans, M.G., Heath, T., Shuttleworth, E. (Forthcoming). Low Cost CO2 Sensing: A microcontroller approach in the context of peatland fluvial carbon.

So now you're wondering how to build the sensor yourself. Follow the instructions in the supplementary material and if you get stuck PLEASE GOOGLE and don't be disheartened if it goes wrong the first time. If you have so much fun you want to talk about it get in touch with me on twitter @Brown_SL_.

I highly recommend testing all your soldering and equipment as you go along using a breadboard. This is also an opportunity to set the correct time on the RTC using the example sketch 'DS3231' in the 'RTClib' library. Next all you need to do is copy and paste the text from 'Code_at_publication' into the Arduino IDE and upload it. Plug in your sensor via USB and if everything has worked correctly, you should be able to view the data straight away on the serial monitor. If it hasn't worked, some early things to check are:

1. The Arduino IDE hasn't recognised your board. It doesn't always do this if you're using a non-Arduino version of the boards but I found sometimes I needed to unplug and then plug in again my Arduino too. Go to Tools > Port to check the IDE can see your board in one of the USB COM ports.

2. Solder connections are faulty. Especially if you're new to soldering (as I was at the start of this project), check each soldered breakout board with a breadboard to see if it functions alone. There is loads of documentation online at Adafruit to show you how to connect things to a breadboard.

3. You've forgotton something small. I had nightmares about forgetting the MicroSD card was plugged in. Also check the coin cell battery for the RTC. Both of these things will either cause an error message or give you faulty/weird data.
