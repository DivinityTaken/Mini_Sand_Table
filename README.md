# Mini_Sand_Table
This project started life as an assignment in one of my rapid prototyping classes however it has quickly grown into one of my favorite creations. The original idea was to build a scaled down Sisyphus Table that could sit on a desk as a little desk toy, this idea ended up being successful and the Mini Sand Table was born. 

BOM: [Link](https://docs.google.com/spreadsheets/d/1AzuKBqGoonScOun9C1d-WrM6_qlQOfSEnQ0_XetDFRE/edit?usp=sharing)

The links in the BOM are to AliExpress pages for the cheapest options, the doc will be updated later with Amazon links for easier and faster, but more expensive parts.

Printables: [Link](https://www.printables.com/model/224376-mini-sand-table)

The GitHub will always have the most up to date files, if I make any changes I will update the Printables page, but the GitHub syncs automatically so it'll end up being more up to date.

I used [Sandify](https://sandify.org/) to generate the GCODE for the table. It has a work area of 120x120mm so most of the patterns need to be scaled down. If you want the program to loop you'll have to add M808 L0 to the start GCODE and M808 to the end GCODE when you export from the website. If you are familiar with programming this is effectively a GOTO command, making the program go to the beginning when it gets to the end. More info can be found here: link.

The filename also has to be “auto0.g” for marlin to start running the program as soon as it boots up.

Some Notes:

* All of the parts (except for 1) are printable without supports 
* I recommend 100% infill for the “Sand Cover” piece to stop any light bleed
* The attached PDF is assembly instructions, if you have any feedback on the instructions please let me know

