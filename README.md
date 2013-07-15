<b>Sound Interactivity: openFrameworks + Arduino code.</b>

Demo with IR sensor triggering Gurgle sounds here: https://vimeo.com/70314848

The design calls for 3 IR sensors per mushroom for each of the 3 Sound mushrooms. 120 deg angle per mushroom, so divide by 3 yields 40 degrees per Sensor, which is good wiggle room to prevent beam overlap. 
3 more analog inputs are available on the Arduino UNO if we want touch sensors. 

<b>Breathing:</b> Speed of playback depends on proximity to IR sensors. The closer you are, the faster the breathing. The exhale/inhale sequences are randomly selected from 10 different pairs. 

<b>Accents: </b> This is the scrape.wav file which plays back with no interactivity affecting it

<b>Gurgles: </b> Are triggered by IR sensors. Played at 100% volume