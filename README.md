# Smart-Cane-for-Visually-Impaired-People
We have prepared a smart cane which will help the visually impaired people to walk independently

Arduino plays the role of micro-controller. The Arduino gets initialized by switching it
on. In the event that the visually impaired person needs to go to a specifc place he/she
will initially choose the mode either the speaker mode or vibration mode. ultrasonic
sensors are being used for distance measurement and additionally for obstruction
discovery. For the same, majorly 3 ultrasonic sensors are being utilized. These 3
sensors covers all 3headings (left, centre, right) of the individual. As indicated by the
given figure, the separation between stick to street side (right half of the street)will
be estimated by ultrasonic sensor 1, distance between stick to centre street will be
estimated by ultrasonic sensor 2 and the distance between stick to street side (left
half of the street) will be estimated by ultrasonic sensor 3.

According to system's framework, two modes are being utilizing that are vibrator
mode and speaker mode. On the chance that the encompassing volume is huge,
disabled individual can utilize vibrator mode else he/she can utilize speaker mode
with the goal that guidelines can get pass through speaker.
In the event that the individual picks the vibration mode, the impediment is
identified with the ultrasonic sensor and the sensor will examine for an obstruction
or it will filter if any water body is available or not, as an alert for the individual.
At the point when the obstacle is detected then vibrator will vibrate once and in the
event that water is recognized, the signal will vibrate twice.
Presently on the chance that the individual picks the speaker mode, with the
assistance of speaker which obstacle is there is informed to the individual as an audio.
Later the distance is calculated by the distance formula. The distance which is longest
is chosen as the way for the individual to walk.
