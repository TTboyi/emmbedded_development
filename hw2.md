1. 在自己账户目录下创建子目录hw2，所有要检查的文件都放在这个目录下，文件名字以hw2开头，如hw2.sh等，这时文件的路径应该是： \~/hw2/hw2.sh （‘~'表示你的账户所在更目录，如pi账户，那么完整路径就是/home/pi/hw2/hw2.sh。
2. Write a shell script to control ACT LED of RPi as dipicted in "Interacting with the Onboard LEDs" of Chapter 2. You want to vary the brightness of the LED through a PWM square wave signal at 3 different duty cycles. Without user's input, your script need to be finished running in a minitue with the command: bash hw2.sh.