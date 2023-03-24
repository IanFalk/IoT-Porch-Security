# IoT-Porch-Security
An IoT project for porch security

The idea behind the project was created and driven from watching videos of people’s packages being stolen off their front porch, and watching delivery drivers mishandle packages leading to damaged goods upon arrival.

The program uses an ultrasonic sensor to detect motion on the porch, and when motion is detected it takes a picture that it sends as an email alert. It uses TensorFlow machine learning to detect objects in the picture like packages, people, or cars. In the future I hope to add the ability to include an audio recording in the alert in addition to the picture.

The physical system is made using a Raspberry Pi 3, Logitech C720 USB Camera, a HR-S04 Ultrasonic sensor, and a MAX4466 Microphone amplifier. All programming was done in Python3 using the Thonny Python IDE that comes with the Raspberry Pi operating system. Several open source python libraries were used like OpenCV, TensorFlow, and smtplib. Additionally it uses Google Cloud to host the MySQL database where all of the user data is stored. A google mail, or “gmail”, email account was used as the medium for sending alerts to the user.
