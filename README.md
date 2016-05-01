# OsoYoo 3.5" Touch Screen Raspberry Pi Install

I ended up buying this [$20 Raspberry Pi Case and Touch Screen] 
(http://www.amazon.com/OSOYOO-Display-Monitor-Transparent-Raspberry/dp/B013E0IJVE) thinking that configuration would be fairly easy. I was wrong. It took me a better part of a weekend to figure out.  I put all the files needed here hoping to help someone else. 

## Board Identifcation 

The boards should be fairly clearly marked on the back: 


##V5 Installation

Launch Terminal:

 `cd Documents `
 
 `sudo wget https://github.com/jgamblin/OsoYooTFT/blob/master/LCD_show_v5.tar.gz `
 
 `tar xzvf LCD_show_v5.tar.gz `
 

To enable LCD:

 `cd LCD_show_v5 `
 
 `./LCD35_v35 `
 
 To enable HDMI:

 `cd LCD_show_v5 `
 
 `./LCD_restore `
 
 
##V4 Installation

Launch Terminal:

 `cd Documents`
 
 `sudo wget https://github.com/jgamblin/OsoYooTFT/blob/master/LCD_show_v4.tar.gz `
 
 `tar xzvf LCD_show_v4.tar.gz`
 

To enable LCD:

 `cd LCD_show_v4`
 
 `./LCD35_v4`
 
 To enable HDMI:

 `cd LCD_show_v4`
 
 `./LCD_hdmi`

##V3 Installation

Launch Terminal:

 `cd Documents`
 
 `sudo wget https://github.com/jgamblin/OsoYooTFT/blob/master/LCD_show_v3.tar.gz `
 
 `tar xzvf LCD_show_v3.tar.gz`
 

To enable LCD:

 `cd LCD_show_v3`
 
 `./LCD35_v3`
 
 To enable HDMI:

 `cd LCD_show_v3`
 
 `./LCD_hdmi`
 
##Important Notice
 
*I dont know what I am doing. This could break your system.* 
