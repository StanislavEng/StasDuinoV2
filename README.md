# StasDuinoV2
I had a bit of time still left in the month to work on PCB design (with Autodesk Eagle).  
As a result I attempted to create another Arduino Clone, this time using the SMD ATMega as well as attempt BT capabilities.

At the time I was looking, I was unable to find a decent (reasonably priced) BT module. 
I found a small ESP module after several hours of looking and I created its part to be used. 
However, this chip, as long with other "reasonably priced" BT chips were actual MCUs in the first place,  
it began to feel a bit redundant like using an MCU as a serial converter for programming (heh). 

Additionally, I was not too sure how to properly create communication between the Arduino and the BT.
My idea later (that I had not yet implemented) was hooking up the two via RX/TX lines (which make sense to me)  
and then using MOSFETs to block communication into the ESP while programming the Arduino. 

Otherwise, I changed the serial programmer to an FTDI chip, and instead looked at and referenced other Arduino clone  
datasheets including the Sparkfun RedBoard to see other ways of programming, which was interesting in its own way. 

Overall, after this I want to make one more "Arduino Clone", instead using a SAMD21, finally adding in the BT,  
and lastly using Altium (Student version) to replace Eagle and be more industry relatable. 

I made almost everything myself. I ended up getting lazy and impatient again and imported the push button (I think)  
and the... things for the pinouts. 

Was fun, still took about two revisions for a trace out I was happy with. 

![image](https://user-images.githubusercontent.com/39227553/115813254-b109af80-a3a7-11eb-8191-ad5eaf95c9e6.png)
