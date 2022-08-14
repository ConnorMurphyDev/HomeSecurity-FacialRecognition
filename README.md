# HomeSecurity-FacialRecognition
Home security through facial recognition and mobile notifications

v0.1 collect facial data and detect/recognize said facial data through camera.

V0.2 (in progress) detect facial movements to ensure the face is not a still picture. A depth camera could be used but would significantly increasee cost when using multiple cameras.

v0.3 prototype, signal the opening to a deadbolt and a Raspberry Pi. Run the same code on the Pi but extend it to use IFTTT to unlock the deadbolt.

v0.4 prototype, add a feature to the program running on the Pi to collect a person's facial data and be able to recognize them as a person who should unlock the door. 

For v0.5 ->  v0.9, Setup a web server and web site. (Most likely Azure or AWS)

The web site becomes the frontend client controlling the connection and communication between the client.
On the website, a user makes an account and connects the client (Pi code) to their account on the server. 
They provide their facial data through the website now, and it's pushed to Pi.
