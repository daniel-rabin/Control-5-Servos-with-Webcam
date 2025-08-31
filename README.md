Python script (on PC):
- Uses MediaPipe for hand tracking
- Calculates finger bend angles
- Sends those 5 values over Wi-Fi (TCP) to ESP32-S3

ESP32-S3:
- Receives angle values
- Maps them to servo PWM values
- Writes to 5 servos via Servo.h

