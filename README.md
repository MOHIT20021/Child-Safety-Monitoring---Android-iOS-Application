# Child Safety Monitoring - Android/iOS Application
 App made via using simulink Matlab
 
# Problem statement
Design and deploy an Android/iOS app for a smart bicycle to help parents monitor their child’s safety.

The smart bicycle has embedded hardware sensors and systems such as a gyroscope, accelerometer, GPS, microphone, and antenna. For this problem statement, assume that your Android/iOS mobile phone (Phone A/sender)  behaves as the smart IoT embedded system and you are riding a (sensorless old-fashioned) bicycle. It should be able to transmit the data to your partner's device (parents’ Android/iOS mobile hereafter referred to as Phone 😎 for warning.)

The child-monitoring Android/iOS app (during cycling) should be able to do the following:

1. Continuously monitor the GPS, accelerometer, and gyroscope data of your phone to determine the following

Fall detection
Boundary crossing (define some geographical coordinates on campus)
Note: Your device should detect actual falls and avoid false detection like bumps or braking.

2. If the cycle goes beyond a particular perimeter,  your device should do the following:
Play a beep alarm sound on your device (Phone A/sender's).
Display the real-time location of phone A(sneder) on phone B (receiver)  and play a beep sound on Phone B.
3. If the cycle falls, your device should do the following:
Play a beep alarm sound on your device (Phone A), with an option to switch OFF the alarm.
Display the real-time location of phone A on phone B and play a beep sound on Phone B.
If the alarm is not switched OFF within 5 seconds by Phone A, a) Switch on the microphone of phone A automatically and start recording. b) Send an SOS from phone A to phone B by transmitting the recorded sound and images using mobile internet network


# Here Sender File should be on the Child's phone and Receiver File should be on the parents phone.
