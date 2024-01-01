# Digispark (ATTINY85) Keystroke Injection
A keystroke injection attack, is a fancier way of saying a device that can type at extremley fast speeds (upwards of 1000wpm). The Digispark ATTINY85 is a development board with various applications and uses, for example controlling [various hardware connected to it via code](https://www.youtube.com/watch?v=4g6IkBWWMxM). In this case however I followed along a tutorial by [TheWP](https://www.youtube.com/user/TheWP) on using it to create a keyboard injection tool.

Of course this is not the only application for the tool but this is just an example demonstration of the powerful applications. In the near future I hope to explore this USB development board and use it to experiment with various functions.

## DIY
The ATTINY85 model from Digispark is available nearly everywhere (as far as Canda goes), I purchased one off [AliExpress](https://www.aliexpress.com/wholesale?trafficChannel=main&d=y&CatId=0&SearchText=digispark+attiny85&ltype=wholesale&SortType=total_tranpro_desc&groupsort=1&page=1) for under $5 CAD and it came with a couple digital pins. I highly suggest following along the tutorial by [TheWP](https://www.youtube.com/user/TheWP) linked [here](https://www.youtube.com/watch?v=kcZUIHUHhTA) as it is very comprehensive and easy to follow along.

## Setup
1. Download &  Install the Arduino IDE from [here](https://www.arduino.cc/en/Main/Software)
2. Add DigiSpark drivers to Arduino IDE via Additional Boards Manager URLs.
    - Open Arduino IDE
    - Go to File > Preferences
    - Add the following URL to the Additional Boards Manager URLs: `http://digistump.com/package_digistump_index.json`
3. Install DigiSpark drivers via Boards Manager.
    - Open Arduino IDE
    - Go to Tools > Board > Boards Manager
    - Search for `Digistump AVR Boards` and install the latest version.
4. Select Digispark Board under Tools > Board menu.
5. Write your code, and upload it to the board.
6. After it compiles it will prompt you with a message to plug in the board. Plug it in and wait for it to upload, and it will automatically run the code once before ejecting itself.


## Code
The python script for converting Rubber Ducky scripts to Arduino Code is created  by [AdvancedNewbie](https://github.com/AdvancedNewbie/), however it uses Python 2.7x and I wil be porting into Python 3x in the near future. I have saved it in my repository as an archive incase the code gets deleted in the near future.

The drivers for this development board can be found on DigiSpark's releases page [here](https://github.com/digistump/DigistumpArduino/releases).
