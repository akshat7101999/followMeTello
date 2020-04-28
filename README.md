# followMeTello
Challenge was to put AI in a DJI Tello Drone which comes with inbuilt camera. Made my drone to follow me where-ever i go using open-cv. Drone also records at high frame rate i.e. while opencv is processing a frame, other frames sent by drone are being saved in the directory continuously. Also added speech recognition so that it hears my commands too.
Steps to run :-
1) You will need to run the FaceDetector.py first.
2) Then connect tello to your Lappy and run AirPro.py.
3) If you want tello to follow you, you can leave it here and comment out any speech recognition code that might be causing           crash of the program in the AirPro.py(most probably it will be commenting the code which reads csv files ) but if you want the audio commands recognition to work then install snowboy hotword first and but the files in the SpeechRecognition into it.
4) Code should run just fine !
