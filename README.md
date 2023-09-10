# FM Radio Intruder and Creator
Author: R.Shashank Kanna
# Disclaimer
This webpage is intended for educational purposes only. We do not endorse or encourage any illegal or unethical use of hacking tools or hardware. The information provided is theoretical and should be used responsibly and within legal boundaries. We are not liable for any misuse or consequences resulting from the information on this webpage. Always prioritize ethical practices and respect the privacy and security of others.

# About
FM Radio being gaint in mass media communication, what if there is a way to gain access to that platform. Normally FM stations use sophisticated hardware to transmit data through a particular frequency.

Imagine building a device which can do the same but also that can intrude pre-existing frequency and play anything as per the user wish.

# Requirements
 - Raspberry Pi 0/2/3/3b/3b+/4
 - Power source
 - Monitor, if ssh is not enabled
 - An antenna (just a wire can be used)
# Raspberry Pi setup
Download, install and boot the Raspberrian OS to your Pi and open terminal to run the following commands:
 - sudo apt-get install make libsndfile1-dev
 - git clone https://github.com/ChristopheJacquet/PiFmRds.git
 - cd PiFmRds/src
 - make clean
 - make
All the installations and setup are complete
# Working
To run the intruder, u need songs or recordings in for of .wav format. You can use wget command to get the required file.

There are 5 prebuilt audio files for testing.

 - sudo ./pi_fm_rds -freq "frequency" -audio "file.wav"

Run the above commande by replacing "frequceny" and "fie.wav" with your appropriate names.

If need your can add a wire or an antenna on GPIO 4 on your raspberry pi for extra range and clarity.

