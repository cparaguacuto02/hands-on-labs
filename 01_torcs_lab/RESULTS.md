Copy this resutls file and paste it into your own repo to showcase your results! Lab results do not count towards your score you'll receive for your submission, but we encourage you to show off what you learned in the lab!
# Add your experiment results and reflections here
I learnt how to set up a TORCS environment
 I experimented with the Race Car Driving Simulation by changing configurable parameters

# Before
TARGET_SPEED = 100  # Target speed in km/h. Increasing this makes the car go faster but may reduce stability.
STEER_GAIN = 30     # Steering sensitivity. Higher values make the car turn more aggressively.
CENTERING_GAIN = 0.20  # How strongly the car corrects its position toward the center of the track.
BRAKE_THRESHOLD = 0.9  # Angle threshold for braking. Lower values brake earlier.
GEAR_SPEEDS = [0, 20, 40, 80, 100, 180]  # Speed thresholds for gear shifting.
ENABLE_TRACTION_CONTROL = True  # Toggle traction control system.

# Manipulating Steering
Changing parameter STEER_GAIN to 25 made a significant difference. Even though it eventually cut a corner and lap time was invalidated, the racing car was more stable during softer curves without losing control.

# Manipulating Centering
Changed centering parameter to 0.22, however, it unfortunately it still cut the same corner even though it tried to correct.

# Manipulating Steering Again 
Changed steering parameter to 22