# QingHuaCiTone-with-DebounceButton
 “Compose a melody by yourself”

1. Use a potentiometer to change the frequency of tone(pin, frequency, duration)
2. Use a button to record the value of potentiometer as frequency (max 10 values)
3. Press the button for 5 sec to replay the melody you composed

Hint: When a button is pressed, the value of potentiometer is added into melody[] = {frequency1, frequency2, ...., frequency 10}. In other words, 10 values are added into melody[] after pressing the button for 10 times. Then press the button for 5 sec to playback the melody you recorded.
