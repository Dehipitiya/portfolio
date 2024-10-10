---
icon: square-code
---

# IR remote control car with Arduino

I created the IR remote control car I am using the Arduino UNO. Also, the IR receiver module is mainly used to control this robot. Therefore, we can control this robot using any kind of IR remotes. The IR remote control Robots is based on the Arduino UNO board and L293D motor driver shield.

When the Car is powered on, the L293D motor shield and IR receiver module are activated via the Arduino UNO board. Also, the IR receiver the IR rays. Then, when the values are received from an IR remote that matches the program, the gear motors rotate forward and backward according to those values. The motor rotation is done by the motor driver shield.

The special thing needs to keep in mind while making this robot car is that even though we used the L293D motor driver shield, the motor 1 and motor 2 terminals could not be used. This is because these motor1 and motor2 terminals are not functional with the IR receiver library we use. Therefore, we can only use motor3 and motor4 terminals.

{% embed url="https://github.com/1234tharindu/IR_remote_car.git" %}

{% embed url="https://youtu.be/f9xyPXYBlCs?si=rUzVbsBwvDex1jDT" %}
