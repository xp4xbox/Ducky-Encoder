# Ducky Encoder
A USB Rubber Ducky Script encoder written in HTA/VBscript. Requires [duckencode.jar](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Downloads) to be placed in the `c:\temp` folder. Please refer to the [instructable](https://www.instructables.com/id/USB-Rubber-Ducky-Script-Encoder-VBScript/) for more information.

## Usage

1. If you don't already have a folder called temp in your C drive, create one.

2. Install Java if you don't already have it installed:  https://www.java.com/en/

2. Download the `duckencode.jar` from https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Downloads
and place it in your `c:\temp` folder

3. Run `Duck.hta` with the two other files in the same directory, or `Duck.exe` if you are using the standalone .exe version.

4. Paste in your script or open the text file with your code. NOTE: this program only reads .txt files.

5. Hit Encode, and the program will encode your script to a file called `inject.bin` in `c:\temp`

6. Move `inject.bin` to your USB Rubber Ducky.

![pic](https://i.imgur.com/x4HYsXB.jpg)
