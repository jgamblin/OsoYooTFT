# OsoYoo 3.5" Touch Screen Raspberry Pi Install

I ended up buying this [$20 Raspberry Pi Case and Touch Screen] 
(http://www.amazon.com/OSOYOO-Display-Monitor-Transparent-Raspberry/dp/B013E0IJVE) thinking that configuration would be fairly easy. I was wrong. It took me a better part of a weekend to figure out.  I put this together hoping to help someone else. 

## Board Identifcation 

The boards should be fairly clearly marked on the back:

<img src="http://jerrygamblin.com/wp-content/uploads/2016/05/2016-05-01-16.06.46.jpg" width="400">


##V5 Installation

From the Terminal:

 `cd Documents `
 
 `sudo wget https://github.com/jgamblin/OsoYooTFT/blob/master/LCD_show_v5.tar.gz `
 
 `tar xzvf LCD_show_v5.tar.gz `
 

To enable LCD:

 `cd LCD_show_v5 `
 
 `./LCD35_v35 `
 
 To enable HDMI:

 `cd LCD_show_v5`
 
 `./LCD_restore`
 
 
##V4 Installation

From the Terminal:

 `cd Documents`
 
 `sudo wget http://en.kedei.net/raspberry/v4/LCD_show_v4.tar.gz`
 
 `tar xzvf LCD_show_v4.tar.gz`
 

To enable LCD:

 `cd LCD_show_v4`
 
 `./LCD35_v4`
 
 To enable HDMI:

 `cd LCD_show_v4`
 
 `./LCD_hdmi`

##V6 Installation

From the Terminal:

 `cd Documents`
 
 `sudo wget http://en.kedei.net/raspberry/v6/LCD_show_v6.tar.gz`
 
 `tar xzvf LCD_show_v6.tar.gz`
 

To enable LCD:

 `cd LCD_show_v6`
 
 `./LCD35_v6`
 
 To enable HDMI:

 `cd LCD_show_v6`
 
 `./LCD_restore`
 
 ## More Files
 There are [more files here] (http://en.kedei.net/raspberry/raspberry.html).
 
##Important Notice
 
*I dont know what I am doing. This could break your system.* 
