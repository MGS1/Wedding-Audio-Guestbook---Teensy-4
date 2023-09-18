# Wedding-Audio-Guestbook---Teensy-4
Wedding voicemail using a Teensy 4.0 with 4.0 Teensy Audio Shield. Handset is lifted, a pre-recorded greeting plays followed by a beep, then recording starts, saves to an SD card in WAV format, and continues until the handset is replaced. Playback button and on/off switch. Details below:

## APPROXIMATE COST: ~$120 in parts + cost of the phone itself.

This is a 'simplified' step-by-step tutorial (even for those who haven't done something of the sort before) using a Teensy 4.0 with 4.0 Teensy Audio Shield. When the handset is lifted, a custom, pre-recorded greeting message is played followed by a beep. Recording starts, saves to an SD card in WAV format, and continues until the handset is placed back on the 'hook.' A pushbutton allows for playback of the last recorded message. Another push button powers the phone on and off. A pre-recorded "Greeting.wav" audio file stored on the SanDisk Ultra micro SD card must be converted to 16 bit signed 44.1 kHz (using FREE Audacity software) for the software to recognize and then play the message upon picking up the handset.

SIDE-NOTE: I've made approximately 50 phones at this point and regularly respond to YouTube comments (on the original audio guestbook guide) which can be found [here](https://youtu.be/dI6ielrP1SE). Not only have I managed to eliminate some of the hardware this tutorial suggests you buy, but I've taken it a step or two further and improved the overall design to maximize ruggedness and ergonomics (i.e. the only reason to take the phone cover off is to replace batteries). I've not made enough profit from assembling projects for people who buy/send the materials to me nor from the donations I've gotten from helpful input given via Reddit [here](https://www.reddit.com/user/puissantvirtuoso/). I recently converted several phones for a business that fell victim to the patent that recently was awarded to "After the Tone." Here is my Venmo link if you feel so inclined to gift :`https://account.venmo.com/u/Mars-Aurelius`.

## You'll need to download the BETA Teensy Software [here](https://www.arduino.cc/en/software). This is important because it enables MTP files transfer from the micro SD without having to remove it from the phone.
## You'll need to download the project files (in ZIP format) from the original YouTube Video GitHub to upload onto the microcontrolles [here]([https://www.arduino.cc/en/software](https://github.com/playfultechnology/audio-guestbook/tree/main).

I used a simple sodering iron from Walmart for this project. These boards are rugged so there's little worry when soldering. 
#### [30 amp soldering iron from Walmart (located in the auto section)](https://www.walmart.com/ip/Hyper-Tough-30-Watt-Soldering-Iron-with-Stand-and-Electrical-Solder/274899628?wmlspartner=wlpa&selectedSellerId=0&wl13=1895&adid=22222222277274899628_117755028669_12420145346&wmlspartner=wmtlabs&wl0=&wl1=g&wl2=c&wl3=501107745824&wl4=pla-294505072980&wl5=9015392&wl6=&wl7=&wl8=&wl9=pla&wl10=8175035&wl11=local&wl12=274899628&wl13=1895&veh=sem_LIA&gclid=Cj0KCQjwzdOlBhCNARIsAPMwjbykdQrN3S5puudsuJeSOVv7KG2DbdfFBIo_aHOcQ6fOC02kjI1ItnYaAvMiEALw_wcB&gclsrc=aw.ds) - $12

## Below are the items to order:

### [Teensy 4 Audio Board](https://www.amazon.com/gp/product/B07Z6NW913/ref=ox_sc_act_title_2?smid=A2GTSJRNFEVVSP&psc=1) - $18

### [Teensy 4](https://www.amazon.com/PJRC-Microcontroller-Development-Lockable-Version/dp/B09X27NXL5/ref=sr_1_1?crid=37XTZ59CGJ5KI&keywords=teensy+4&qid=1689640360&s=electronics&sprefix=tensy+4%2Celectronics%2C1703&sr=1-1) - $28

### [Mountabled Micro USB port to transfer files from Micro SD directly without removing SD card or phone cover](https://www.adafruit.com/product/4217?gclid=Cj0KCQjw7aqkBhDPARIsAKGa0oKDg6ZUNy0jwFyrbgXlQiEyEXlkNRDUzN44n1SIFiucr9ZN2WgOYWYaAl77EALw_wcB) - $5

### [Power Button On/Off Switch](https://www.amazon.com/dp/B0927153HN?ref_=cm_sw_r_apin_dp_SGKWW03W33SRRYP3TKR0) - $11

### [32 GB SandDisk Ultra Micro SD Card - This card is fast enough for this project, please do not deviate](https://www.amazon.com/SanDisk-Ultra-UHS-I-Memory-Adapter/dp/B00M55C0NS) - $8

### [PlayBack Button Switch](https://www.amazon.com/dp/B09BKXT1J1?ref_=cm_sw_r_apin_dp_HXBY2PMP0RN0EAWKBVA7) - $13

### [24 AWG Wire](https://a.co/d/054YrJi) - $8

## [3xAA Battery Holder to Power this Project](https://a.co/d/df2GFEO) - $7

## [Male/Female Pins/Headers](https://a.co/d/bD6Ysn1) - $9

## Not Required but highly recommended:

### [Gorilla Glue to glue everything down - basically liquid electrical tape](https://www.amazon.com/Gorilla-Construction-Adhesive-Strength-Ounce/dp/B0916KZ598/ref=sr_1_4?crid=35HBFEW48MZNX&keywords=gorilla+glue+clear&qid=1689642099&s=industrial&sprefix=gorilla+%2Cindustrial%2C249&sr=1-4) - $8

### [Heat Shrink tubing to Enforce Solder Joints](https://www.amazon.com/dp/B0BLK98LBM?ref_=cm_sw_r_apin_dp_M30W6KX3CNSPE8XHGHYZ) - $8

### [Skinny Zip-ties for Cable Management](https://www.amazon.com/Inch-120pcs-Nylon-Cable-Multi-colors/dp/B07K2CHPJJ/ref=sr_1_11?keywords=small+zip+ties&qid=1689642314&s=industrial&sr=1-11) - $5
