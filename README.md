This program is used to generate an SVD for the peripheral devices of the ESP32. 

To use it you must provide an esp32.txt file in the directory of the binary.

To produce this esp32.txt file, Adobe Acrobat Pro can be used to open the Technical Reference Manual and copy/paste it to text. 

The code here is written to expect this is exactly how the text file is produced, due to the angled nature of register fields, only Acrobat Pro had a sane enough PDF-to-Text mechanism to work.

Program produces esp32_svd.xml at the end.
