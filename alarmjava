import time
import datetime
import os

# Set alarm time (HH:MM:SS)
alarm_time = input("Enter alarm time (HH:MM:SS): ")

print("Alarm set for:", alarm_time)

while True:
    current_time = datetime.datetime.now().strftime("%H:%M:%S")
    print(current_time)

    if current_time == alarm_time:
        print("Wake up! ⏰")
        os.system("afplay /System/Library/Sounds/Glass.aiff")  # Mac sound
        break

    time.sleep(1)
