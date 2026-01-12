# ⚙️ Working Explanation

1. The ultrasonic sensor emits ultrasonic waves using the **Trig** pin.
2. Waves reflect back from obstacles and are received by the **Echo** pin.
3. Arduino calculates the distance using echo time.
4. If the distance is greater than 10 cm, the robot moves forward.
5. If the distance is less than or equal to 10 cm:
   - Robot stops
   - Robot turns left to avoid the obstacle
6. The process runs continuously in a loop.
