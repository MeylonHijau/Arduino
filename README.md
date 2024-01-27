
# Valorant-Color-Aimbot 

Colorant is a highly efficient Color Aimbot designed to rapidly scan for purple color range on your screen and aim/shoot at it, without any interference with the game memory or files of Valorant.

Unlike conventional video game cheats that rely on the process memory to function, Color aimbots adopt a unique approach by avoiding any memory reading altogether. This innovative approach has the potential to remain undetectable by anti-cheat mechanisms that typically attempt to block memory reads. Additionally, sending input to the video game without triggering any flags can be a challenging aspect to consider.

The primary objective of this project is to showcase a proof of concept, demonstrating the potential of Colorant's novel approach to aimbot technology.

![image](https://user-images.githubusercontent.com/82477000/225608740-5f690006-9cc8-4d88-8a60-cda89d0f936f.png)


## Getting started

#### You will need the following prerequisites:
- [ARDUINO LEONARDO](https://www.amazon.com/Arduino-org-A000057-Arduino-Leonardo-Headers/dp/B008A36R2Y)
- [USB HOST SHIELD](https://www.amazon.com/Compatible-Arduino-Support-Android-Function/dp/B0B3TH6H6N)

The initial setup can be a bit challenging, as you will need to set up your Arduino and USB host shield. It is important to note that some USB shields may come unsoldered, so you may need to solder both 5V ports and the bottom 3.3V port to ensure that it works correctly. For further clarification, you can refer to [THIS](https://www.youtube.com/watch?v=nBttwvgNOr8) video.

Next, you will need to download and install Python, with [Version 3.8]([https://www.python.org/ftp/python/3.8.0/python-3.8.0-amd64.exe](https://www.python.org/ftp/python/3.12.1/python-3.12.1-amd64.exe)) being recommended as it was the version used to develop this project. Once Python is installed, you can download Colorant and install the necessary dependencies by using the command `pip install -r requirements.txt`.

To utilize the Arduino board as a computer mouse, the user can upload the Arduino.ino sketch to the board via the Arduino IDE. This sketch can be located within the [Arduino](https://github.com/hafyzwithawhy/Colorant/tree/main/Arduino) folder. The process involves connecting the Arduino board to the computer, opening the Arduino IDE software, selecting the appropriate board and port, and uploading the sketch. By completing these steps, you can transform their Arduino board into a functional computer mouse, allowing for the control of the computer's cursor and clicking functions through the board's hardware.

With the prerequisites and dependencies installed, you can now run the `main.py` file, which is the main entry point of the program. You do not need to make any changes to the code, as it is ready to use.


